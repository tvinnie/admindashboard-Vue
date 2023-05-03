<template>
  <Bar id="mychartId" :options="chartOptions" :data="chartData" />
</template>

<script>
import Data2 from '../utils/Data.js'
import { Bar } from 'vue-chartjs'
import {
  Chart as ChartJS,
  Title,
  Tooltip,
  Legend,
  BarElement,
  CategoryScale,
  LinearScale
} from 'chart.js'

console.log(Data2)

ChartJS.register(CategoryScale, LinearScale, BarElement, Title, Tooltip, Legend)

export default {
  name: 'BarChart',
  components: { Bar },
  data() {
    const yearArray = []
    const values = []

    Data2.forEach((data) => {
      console.log(data.year)
      yearArray.push(data.year)
      values.push(data.userGain)
    })

    return {
      // yearData: "",
      chartData: {
        labels: yearArray,
        datasets: [
          {
            label: 'Users Gained',
            data: values,
            backgroundColor: ['#b30000', '#1a53ff', '#00b7c7', '#5ad45a', '#ebdc78'],
            borderColor: 'black',
            borderWidth: 2
          }
        ]
      },
      chartOptions: {
        responsive: true
      }
    }
  }
}
</script>

<template>
  <Line id="mychartId" :options="chartOptions" :data="chartData" />
</template>

<script>
import Data2 from '../utils/Data.js'
import { Line } from 'vue-chartjs'
import {
  Chart as ChartJS,
  CategoryScale,
  LinearScale,
  PointElement,
  LineElement,
  Title,
  Tooltip,
  Legend
} from 'chart.js'

ChartJS.register(CategoryScale, LinearScale, PointElement, LineElement, Title, Tooltip, Legend)

export default {
  name: 'LineChart',
  components: { Line },
  data() {
    const yearArray = []
    const values = []

    Data2.forEach((data) => {
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

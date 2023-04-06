# FrontEnd2
Practicas frontend
function adjustChartSize() {
  const parentFrame = document.getElementById('parentFrame');
  const legendContainer = document.getElementById('legend-container');
  const chartContainer = document.getElementById('chart-container');

  const parentHeight = parentFrame.offsetHeight;
  const parentWidth = parentFrame.offsetWidth;
  const legendHeight = legendContainer.offsetHeight;

  const chartHeight = parentHeight - legendHeight;
  chartContainer.style.height = `${chartHeight}px`;
  chartContainer.style.width = `${parentWidth}px`;
}



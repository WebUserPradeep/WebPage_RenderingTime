# WebPage_RenderingTime
This repo demonstrate how to capture the web page rendering time on the browser using Fiddler. 

Abstract:
Often during performance testing of the web applications, monitoring the page rendering time on the browsers (Chrome,Safari,Edge,Mozilla Firefox etc.) is neglected.
As the load testing tools are more alligned to capture server side response time.
Hence, the session inspector tool like Fiddler can help in Agile development to capture single user page load time for each sprints.
This response time can further be used as comparison report to validate if any transaction response time is deterioted.

Steps:
  1. Launch the web application on any browser (Chrome,Edge,Safari etc.)
  2. Start Fiddler
  3. With each request sent to server from the browser, capture page load time along with the backend call timings
  4. Log the time taken for all page components (.js,css,xhr) to render with single user load

Please have look at attached document which provides detailed screenshots of capturing page response time on browser.

Download Link: https://assignmentchef.com/product/solved-ece495-assignment-6-extended-kalman-filter-using-landmark-data
<br>
<ul>

 <li>To understand how to apply the Extended Kalman Filter (EKF) to a practical problem</li>

 <li>To learn how to compute the necessary Jacobians to linearize nonlinear system dynamics</li>

</ul>

You are provided with a sequence of measurements of known landmark locations in a given area, as well as a sequence of IMU data that measures how the vehicle is moving in the workspace. Your objective is to fuse these two datastreams using an EKF to estimate where the vehicle is in the workspace. The measurement model maps the position of the landmarks to a range and bearing relative to the vehicle, similar to how a LIDAR scan would capture the landmark location. Further details of the problem are given in the Jupyter notebook, which you will complete and submit.

<h1>Resources and Instructions</h1>

There are 3 TODO sections to complete in the given Jupyter notebook:

<ol>

 <li>Write the measurement_jacobian() function, which should compute the measurement Jacobian for a given landmark location and the current state of the vehicle,</li>

 <li>Write the measurement_update() function, which performs the necessary update to the state and the covariance estimate using a landmark’s true location as well as its LIDAR range and bearing estimate.</li>

 <li>Complete the main Kalman filter loop, which will recursively estimate the state of the vehicle as it progresses through the workspace.</li>

</ol>

<h1>Deliverables</h1>

HTML output: In the Jupyter Notebook, go to File &gt; Download as &gt; HTML (.html). Submit a ZIP file containing the HTML output and the PDF file.

<strong>Run all code blocks before downloading the HTML.</strong>

Please follow the naming convention for your zip file: a6_&lt;user_id&gt;.zip .
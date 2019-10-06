<h1 style='text-align:center'>docker_php5.4</h1>
<br>
<p>
    This docker configuration builds a set of bound containers for php 5.4 and mysql 5.7.
    As a server for static files we use nginx, for other requests Apache is used
</p>
<h2 style='text-align:left;'>How to make it workable</h2>
<ul>
<li>Change server_name in nginx congig</li>
<li>Add in the end of hosts file redirecting to the localhost for serve_name and pma.server_name</li>
<li>Execute in terminal docker-compose up --build </li>
</ul>

<!DOCTYPE html>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Julius+Sans+One&family=Montserrat" rel="stylesheet">

<!-- 600 x 800 PDF format  -->

<html>

<style>
:root {
  --BORDER:1px solid red;
  --COLOR_GRAY:#ddd;
}
body {
  background:#E1E7ED;
  margin:0px;
  padding:0px;
  padding-left:2px;
  font-size:12px;
}
table {
  border-collapse: collapse;
}
table td{
  padding:0px;
  margin:0px;
  border:var(--BORDER);
}
table td img {
  width:16px;
  height:16px;
  padding-top:2px;
  padding-right:2px;
  padding-left:8px;
}
.column
{
  font-family:"Montserrat";
  padding:15px;
  margin:0px;
  font-weight:500;
  font-style: normal;
  min-height:1020px;
  color:#4d4d4d;
}
.column p{
  font-size:14px;
}
#pane-left {
  width:180px;
  background:#27415C;
  color:white;
  border-radius: 25px 0px 0px 25px;
}
#pane-right {
  width:570px;
  background:#fff;
  border-radius: 0px 25px 25px 0px;
}
#contact {
  border:var(--BORDER);
  text-align:center;
}
#contact a {
  font-size:12px;
  color:#3d71c4;
}
.divider-line {
  width:100%;
  border:0px solid var(--COLOR_GRAY);
  border-top-width:2px;
  margin-top:5px;
  padding-top:5px;
}
.spacer-left {
  min-height:40px;
  border:var(--BORDER);
}
.spacer-right {
  min-height:40px;
  border:var(--BORDER);
}
#name {
  font-size:25px;
  border:var(--BORDER);
}
#title {
  font-size:16px;
  border:var(--BORDER);
  font-weight:600;
  color:#3771a3;
}
.key-title {
  font-size:14px;
  font-weight:600;
}
.key-header {
  font-size:14px;
}
.key-def {
  font-size:11px;
}

.exp-title {
  font-size:13px;
  width:100%;
  font-weight:600;
  border:var(--BORDER);
}
.exp-date {
  float:right;
  font-size:13px;
  color:#4d4d4d;
  font-weight:400;
}
.exp-company {
  font-size:14px;
  color:#3771a3;
  font-weight:600;
  padding-top:4px;
}
</style>

<table>
  <td>
  <div class="column" id="pane-left">
    <div id="name">CLINTON ELLYSON</div>
    <div class="spacer-left"></div>
    
    <div class="key-title">KEY ACHIEVEMENTS</div>
    <div class="divider-line"></div>
    <div class="key-header">30% Increase uptime</div>
    <div class="key-def">Migrated all studios to universal operations</div>
    
    <br><br>

    <div class="key-title">PASSIONS</div>
    <div class="divider-line"></div>
    <div class="key-header">30% Increase uptime</div>
    <div class="key-def">Migrated all studios to universal operations</div>
    </div>
  </div>

  <td>
  <div class="column" id="pane-right">
    <div id="title">Director, Operations and Site Reliability Engineering | Strategic Leadership | Process Optimization | Incident Management </div>
    <div id="contact">
      <img src="email.jpg" /><a href="mailto:cellyson78@gmail.com">cellyson78@gmail.com</a>
      <img src="link.jpg" /> <a href="https://linkedin.com/in/clint-ellyson-2b730580">linkedin.com/in/clint-ellyson-2b730580</a>
    </div>
    <div class="spacer-right"></div>
    
    <div class="key-title">SUMMARY</div>
    <div class="divider-line"></div>
    <p>With over 22 years of experience within Operations and Information Technology Infrastructure and over 12 years of Team Leadership.</p>
    
    <br><br>

    <div class="key-title">EXPERIENCE</div>
    <div class="divider-line"></div>

    <div class="exp-title">Director, Site Reliability Engineering & Operations<div class="exp-date">2022 - PRESENT</div></div>
    <div class="exp-company">Take-Two Interactive<div class="exp-date">New York, NY</div></div>
    <li>test</li>
    <li>test</li>
    <li>test</li>
    
    <br>
    
    <div class="exp-title">Senior Manager, Site Reliability Engineering<div class="exp-date">2012 - 2022</div></div>
    <div class="exp-company">Zynga<div class="exp-date">San Francisco, CA</div></div>
    <li>test</li>
    <li>test</li>
    <li>test</li>
    
    <br>
    
    <div class="exp-title">JP Morgan and Chase<div class="exp-date">2005 - 2012</div></div>
    <div class="exp-company">Zynga<div class="exp-date">Pleasanton, CA</div></div>
    <li>test</li>
    <li>test</li>
    <li>test</li>
  </div>
</table>

</html>

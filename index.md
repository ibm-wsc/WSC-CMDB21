<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.0/jquery.min.js"></script>
<script src="./core-min.js"></script>
<script src="./md5-min.js"></script>
<script src="./wildfire-labs.js"></script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

## Welcome

Thank you for attending the Washington Systems Center (WSC) Db2 for z/OS REST and Hybrid Cloud Virtual Wildfire Workshop.


Click [here](Db2 for zOS REST and Hybrid Cloud Presentation.pdf){:target="_blank"} to download the presentation.

## Accessing the hands-on lab

Click [here](CMDB21 Virtual Access Guide.pdf){:target="_blank"} to read the instructions for how to access the Windows environment via a Remote Desktop application or a Web Browser.

The lab instructions are available for download for your convenience.

  Lab #1 Db2 for z/OS Native REST Services: [here](Db2 for zOS REST and Hybrid Cloud - Lab 1 v4.0.pdf){:target="_blank"}.
  Lab #2 z/OS Connect Integration and OpenAPI 2 [here](Db2 for zOS REST and Hybrid Cloud - Lab 2A v4.0.pdf){:target="_blank"}.
  Lab #3 (optional) z/OS Connect Integration and OpenAPI 3 [here](Db2 for zOS REST and Hybrid Cloud - Lab 2B v4.0.pdf){:target="_blank"}.

## Remote System Credentials 

**Please enter the email address you used for registration to retrieve your unique log in details.**

<form onsubmit="return false;">
<div class="input-group mb-3 col-6">
<span class="input-group-text" id="basic-addon1">@</span>
<input type="email" class="form-control" placeholder="Registration Email" aria-label="Email" aria-describedby="basic-addon1" id="registration-email" maxlength="50" required oninput="validate();">
</div>
<div class="col-6">
<button id="btn-submit" class="btn btn-primary" type="submit" onclick="getLab(document.getElementById('registration-email').value)" disabled>Submit</button>
</div>
</form>
<div id="lab" class=".container .text-monospace">
<em>Note you will need a confirmed registration to access the lab.</em>
</div>

## Help
Having trouble with labs? Send an email to [Keziah Knopp](mailto: keziah.knopp@ibm.com) and we will help you sort it out.

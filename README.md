# Detect_Zawgyi_installed
This Javascript is designed to find whether it is installed "zawgyi-one". To decide which font should be display in websites.

## <a target="_blank" href="https://cdn.rawgit.com/LeonarAung/Detect_Zawgyi_installed/79852cd1/test.html">Test Demo</a>


Step 1 ### include jquery
<script src="https://code.jquery.com/jquery-1.12.4.js"></script>


Step 2 ### include script
<script src="https://cdn.rawgit.com/LeonarAung/Detect_Zawgyi_installed/3383a119/zg_detect.js"></script>


Setp 3 ### Find Zawgyi
window.onload = function () { 
	detectZawgyi.start(); //be sure after pageLoad
	zginstalled=detectZawgyi.found("zawgyi-one");
	console.log(zginstalled);alert(zginstalled);
	$("#res").text("ZawGyi installed = "+zginstalled);
}	


## Author

* **[Leonar Aung](https://github.com/LeonarAung)**
For any bug, please contact leonaraung1990@gmail.com


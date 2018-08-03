# Detect_Zawgyi_installed
This script is designed to find whether "zawgyi-one" is installed or not to decide which font should be display in websites.(To switch zawgyi or unicode and others). Not only can test "zawgyi-one" but also for every font with name parameter(replace in ("zawgyi-one") to another name).

## <a target="_blank" href="https://cdn.rawgit.com/LeonarAung/Detect_Zawgyi_installed/79852cd1/test.html">Test Demo</a>


### Step 1 - include jquery
<script src="https://code.jquery.com/jquery-1.12.4.js"></script>


### Step 2 - include script
<script src="https://cdn.rawgit.com/LeonarAung/Detect_Zawgyi_installed/3383a119/zg_detect.js"></script>


### Setp 3 - Find Zawgyi
window.onload = function () { <br/>
	detectZawgyi.start(); //be sure after pageLoad<br/>
	zginstalled=detectZawgyi.found("zawgyi-one");<br/>
	console.log(zginstalled);alert(zginstalled);<br/>
}	

## Our Policy
Commercial Usage,websites that including ads,sell something, is not allowed for 'Detect_Zawgyi_installed'. Contact to developer .

## Author

* **[Leonar Aung](https://github.com/LeonarAung)**
For any bug, please contact leonaraung1990@gmail.com


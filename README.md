<p align="center">
<a href="https://dscvit.com">
	<img src="https://user-images.githubusercontent.com/30529572/72455010-fb38d400-37e7-11ea-9c1e-8cdeb5f5906e.png" />
</a>
	<h2 align="center"> Iris Web Backend </h2>
	<h4 align="center"> This is a service to find the shortest path between two wikipedia pages by going through links in a page <h4>
</p>

---
[![DOCS](https://img.shields.io/badge/Documentation-see%20docs-green?style=flat-square&logo=appveyor)](https://documenter.getpostman.com/view/9876592/T17Q64bY) 


## Functionalities
- [X] API to return shortest path between two pages
- [X] API to discover nodes from one given page
- [X] Visualization Tool

<br>


## Instructions to run

* Pre-requisites:
	- Python and pip installed
	- An active internet connection
	
* Create and activate the virtual environment
```bash
sudo pip3 install virtualenv
virtualenv env
```
* Now for Windows:
```bash
.\env\Scripts\activate
```

* For MacOS and Linux
```bash
source env/bin/activate
```

* Install the dependencies 
```bash
pip3 install -r requirements.txt
```

* To start the server

```bash
export FLASK_APP=main.py
flask run
```

* To start the visualization tool

```bash
python3 vis.py
```
## Contributors

<table>
<tr align="center">


<td>

Md Hishaam Akhtar

<p align="center">
<img src="https://media-exp1.licdn.com/dms/image/C5103AQF78B1xleVjmg/profile-displayphoto-shrink_200_200/0?e=1599091200&v=beta&t=h8dPr3Nozs8ZNIJZeLzuGm2Fr2TiN9xdXpcFuCIVg3Q" width="150" height="150" alt="Md Hishaam Akhtar">
</p>
<p align="center">
<a href = "https://github.com/mdhishaamakhtar"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36"/></a>
<a href = "https://www.linkedin.com/in/md-hishaam-akhtar-812a3019a/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/>
</td>
<td>

Sharanya Mukherjee

<p align="center">
<img src="https://media-exp1.licdn.com/dms/image/C5103AQFG6U5n2wua8A/profile-displayphoto-shrink_200_200/0?e=1599696000&v=beta&t=BuWcQtHSl-MrHvNSwD2RZ8fZQbPie8R3kK8tJgT8ztA" width="150" height="150" alt="Sharanya Mukherjee">
</p>
<p align="center">
<a href = "https://github.com/sharanya02"><img src = "http://www.iconninja.com/files/241/825/211/round-collaboration-social-github-code-circle-network-icon.svg" width="36" height = "36" alt="GitHub"/></a>
<a href = "https://www.linkedin.com/in/sharanya-mukherjee-73a2061a0/">
<img src = "http://www.iconninja.com/files/863/607/751/network-linkedin-social-connection-circular-circle-media-icon.svg" width="36" height="36" alt="LinkedIn"/>


</td>

</table>
<br>
<br>

<p align="center">
	Made with :heart: by <a href="https://dscvit.com">DSC VIT</a>
</p>


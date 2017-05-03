# Citiy Council Leipzig Recent Papers

This is a scraper that runs on [Morph](https://morph.io). To get started [see the documentation](https://morph.io/documentation)

Install docker: See instructions on
[store.docker.com](https://store.docker.com/search?type=edition&offering=community)

Build docker image:
`sudo docker build -t jrlover/leipzig_scraper .`

Use docker image to execute scraper:
Calling `sudo docker run jrlover/leipzig_scraper` will process `"https://ratsinfo.leipzig.de/bi/vo020.asp?VOLFDNR=1003952"`by default, with `sudo docker run jrlover/leipzig_scraper "https://ratsinfo.leipzig.de/bi/vo020.asp?VOLFDNR=1003952` you can process any other paper
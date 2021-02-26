# kafka-java-app
## Group Members:
 - Golla Durga Prasad
 - RaviTeja Pagidoju
 - Gopichand Bandarupalli
 - Pruthvi Naskanti
 - Shiva Rama Krishna Vodnala
 - Sai Krishna Emmadishetty
 
 <table>
<td align="center"><a href="https://github.com/GD-Prasad"><img src="https://avatars.githubusercontent.com/u/59986885?s=400&u=df8057f5d9aa0936da702cdb1a5a776ceddf12a5&v=4" width="100px;" alt=""/><br /><sub><b>GD Prasad</b></sub></a><br /></td>

<td align="center"><a href="https://github.com/RaviTeja444"><img src="https://github.com/chanduhvg/Flink-Fraud-Scala/blob/main/Ravi_pic.jpeg?raw=true" width="100px;" alt=""/><br /><sub><b>Ravi Teja Pagidoju</b></sub></a><br /></td>

<td align="center"><a href="https://github.com/chanduhvg"><img src="https://avatars.githubusercontent.com/u/60024244?s=460&u=1f54a606cfb5ca1af59d89980ccd0597c0794b17&v=4" width="100px;" alt=""/><br /><sub><b>Gopichand Bandarupalli</b></sub></a><br /></td>

<td align="center"><a href="https://github.com/pruthvi-naskanti"><img src="https://github.com/chanduhvg/Flink-Fraud-Scala/blob/main/Pruthvi_pic.jpg?raw=true" width="100px;" alt=""/><br /><sub><b>Pruthvi Naskanti</b></sub></a><br /></td>

<td align="center"><a href="https://github.com/srkvodnala"><img src="https://avatars.githubusercontent.com/u/28599511?s=400&u=b1f6f569110d0150f844184d33a3d7b8e0a4dc4b&v=4" width="100px alt=""/><br /><sub><b>Shiva Rama Krishna</b></sub></a><br /></td>

<td align="center"><a href="https://github.com/Saikrishna1545"><img src="https://avatars.githubusercontent.com/u/60013018?s=460&u=4687be0646ecbb59bd281276c302eba966ff5f64&v=4" width="100px;" alt=""/><br /><sub><b>Sai Krishna Emmadishetty
</b></sub></a><br /></td>

</table>

# Ravi Teja Pagidoju&nbsp;

## Contibution
- Apache FLink Fraud detection on Even Number using java

## Installables
- Java installed on machine
- Apache flink installed(>2)
- Netbeans IDE installed
- Netcat installed

## Steps for Execution of Even Number Fraud Detection
- Add flink dependencies in the pom.xml file to use flink methods in java code.
- Build the application to make sure all the dependencies are downloaded/added to the project.
- Before running the java main class(App.java),start the ncat server on port 9000.
- Java code written using flink stream methods to listen on port 9000.
- Now run the java application main class which starts listen to port 9000.
- Enter a number in ncat server(powershell/cmd) and check if its a even or fraud in the netbeans output window.
- used ncat commands
- ```ncat -lk 9000```

## References
- https://nmap.org/ncat/
- https://nmap.org/ncat/guide/ncat-usage.html
- https://ci.apache.org/projects/flink/flink-docs-stable/dev/datastream_api.html



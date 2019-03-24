# IoT Engineering
## Hands-on of lesson 6
For slides and example code, see [lesson 6](../../../fhnw-iot/blob/master/06/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) Bluetooth LE, 20'
* Run the previous Bluetooth LE examples on the Pi.
* Make sure Node.js, npm and Noble are all installed.
* Use the .js link on each page or check the main repo.
* To run a Node.js program my.js, type ```$ node my.js```
* Use the nRF5280 [HRM BLE Peripheral](https://github.com/tamberg/fhnw-iot/blob/master/05/Arduino/nRF52840_HrmBlePeripheral/nRF52840_HrmBlePeripheral.ino) for testing.

### b) Web client &amp; service, 20'
* Run the previous Web client and service examples.
* Use the .js link on each page or check the main repo.
* To run a Node.js program _my.js_, type: ```$ node my.js```
* To display the IP address on the Pi, type: ```$ ifconfig```
* Then access http://IP:8080/ or https://IP:4443/ 

### c) Remote access, 10'
* Install a [Ngrok](https://ngrok.com/), [Pagekite](https://pagekite.net/) or [Yaler](https://yaler.net/) relay service dæmon.
* Configure it to publish the secure Node.js Web service.
* Submit the URL to access your Web service via Slack.

### d) Putting it all together, 30'
* Choose one of the BLE to Wi-Fi gateway use cases.
* Implement it combining the above building blocks.
* For the backend, use a relay service or ThingSpeak.
* Make it work end-to-end first, then make it robust.

### Submitting results
* [Commit and push](#git) local changes to your repository.
* Want a review? [Create an issue](../../issues/new), mention me (@tamberg).

## Tools
### Git
On your computer
* In the hands-on repository [fork for your class](../../network/members), in README.md, click the _GitHub Classroom link_.
* Once you accept the assessment, you get a personal, private repository URL for your _USER_NAME_:<pre>
http://github.com/fhnw-iot-CLASS/fhnw-iot-work-06-USER_NAME</pre>

On your computer or Raspberry Pi
* Clone the repository<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Add a file<pre>
    $ git add FILE</pre>
* Commit changes<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Push changes<pre>
    $ git push</pre>

## Wiki
- [IoT Engineering Wiki](https://github.com/tamberg/fhnw-iot/wiki)

## Support
- [IoT Engineering Slack](https://fhnw-iot.slack.com/)

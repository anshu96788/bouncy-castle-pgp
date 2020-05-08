# bouncy-castle-pgp

## Getting Started
These instructions will get you a copy of the project up and running on your intregration server for development and testing purposes.
### Prerequisites
1. SoftwareAG integration server.
2. SoftwareAG Designer.
### Importing the project to IS
1. Download the zip file .
2. Go to your SoftwareAg folder then IntegrationServer\instances\default\replicate\inbound.
3. Paste your zip file there.
![Annotation 2020-05-08 141153](https://user-images.githubusercontent.com/60179170/81388167-82161180-9135-11ea-8e06-27c4f659ee8a.png)
4. Start integration server from your Start menu.
5. Go to your browser then visit http://localhost:5555/
6. Default username: Administrator
           password : manage
7. Click on Packages then Install Inbound Releases.
![jj](https://user-images.githubusercontent.com/60179170/81390581-55fc8f80-9139-11ea-9990-5665249e2cdc.png)
8. Select the zip file and click Install Realease.
![jj](https://user-images.githubusercontent.com/60179170/81391931-8ba27800-913b-11ea-9d26-e158c065bcd2.png)
9.  Shut Down and Restart your integration server.
![jj](https://user-images.githubusercontent.com/60179170/81392418-4468b700-913c-11ea-8ba8-9d21e8028140.png)
## Run the java services
1. Start integration server.
2. Open your SoftwareAG Designer and connect to the server. To connect right click on Default package and click on connect to the server option.
![jj](https://user-images.githubusercontent.com/60179170/81392609-898ce900-913c-11ea-82fa-126452b990b8.png)
3. After you have successfully connected double click on Default package and select WxPGPUtils.
![jj](https://user-images.githubusercontent.com/60179170/81392929-0ddf6c00-913d-11ea-9d7d-25a8f8809d27.png)
4. Open any one of the four Java Services.

## Fixing import error
1. If you are facing any import error click on the red mark in fornt of the error line and then click Fix Project Setup..
![jj](https://user-images.githubusercontent.com/60179170/81393821-97dc0480-913e-11ea-9086-a546d5bea370.png)
2. Then click on "here" option for more and then click on Add external JARs.<br />
![Annotation 2020-05-08 151901](https://user-images.githubusercontent.com/60179170/81395095-aa573d80-9140-11ea-9d38-b91ab29172d9.png)
3. Select the two jar from SoftwareAG_x\IntegrationServer\instances\default\packages\WxPGPUtils\code\jars\static. 
![Annotation 2020-05-08 151901](https://user-images.githubusercontent.com/60179170/81394879-4df41e00-9140-11ea-91b7-c035a72f8104.png)
4. And then click on Apply and Close. This will fix the error.<br />
![Annotation 2020-05-08 151901](https://user-images.githubusercontent.com/60179170/81394495-a0810a80-913f-11ea-8432-fca2bd05e724.png)







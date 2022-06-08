# UiPath-Configuration-Management
The implementation of configuration management using UiPath Apps, Data Services and integration into UiPath Studio. All collateral is stored in this repository.

There are multiple different ways that configuration can be managed for automation solutions - even the cross-toolset solutions. The key considerations should be around how to implement and control the configuration items, the middleware and the process:
![Config Management](https://user-images.githubusercontent.com/26733937/172576827-068a3a79-bff9-481e-acce-f6e3be914aba.png)

The approach highlighted in this repository is the use of UiPath Apps and Data Services integrated into Studio (using the Data Services library provided by UiPath). 

## Getting Setup

### UiPath Data Services
Use the JSON file located in the **UiPath Data Services Export** folder and import it into your instance of Data Services. 

**Please Note:** if you already have entities, first export your schema and add the "Config" entity (from the file referenced above) to your schema and import your own schema that includes the "Config" entity.

![image](https://user-images.githubusercontent.com/26733937/172580369-34a0657b-c965-4bcb-a591-b77500a09bc5.png)

### UiPath Apps
Import the file found in the **UiPath App Clone** folder to your instance of UiPath Apps.

![image](https://user-images.githubusercontent.com/26733937/172580724-09507b3a-f5fd-4e2c-8124-412c0f2ee364.png)

### UiPath Studio
Use the solution located in the **UiPath Studio Implementation** folder to test that eveything works. You'll need to reconnect the correct entity.

![image](https://user-images.githubusercontent.com/26733937/172580596-c692d5c8-047f-409a-ae31-80e97bd704f7.png)

If you get stuck, feel free to follow The JPanda blog post explaining the steps in greater detail.

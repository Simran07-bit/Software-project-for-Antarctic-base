[Form.pdf](https://github.com/Simran07-bit/Software-project-for-Antarctic-base/files/6396190/Form.pdf)

 
# Planning and Requirements for Antarctic base 
## Work Breakdown
### 1. Detailed research
### 2. Hiring manpower and skilled worker
#### 2.1 Scientist
#### 2.2 Engineer
#### 2.3 Weather forecaster
#### 2.4 Health worker
### 3. Providing hospitable environment
#### 3.1 Food and water
#### 3.2 Accomodation
### 4. Equipments and devices
#### 4.1 Setting up
#### 4.2 Checking functions
### 5. Monitoring and identifying environmental hazzards
### 6. Health and safety of the worker

![AON graph](https://user-images.githubusercontent.com/83198969/116499432-b94d7780-a8de-11eb-9373-8ed7de78f406.png)

## User stories

1. As a software developer, I want to do deatiled and proper research about the base so that I can ensure the msooth operation of the base.

2. As a weather forecaster, I want to know that conditions of weather and temperature beforehand so that I cam control the unpredictable situations. 

3. As an engineer, I want to check all the equipments and devices regularly so that I can make sure all the tools and instruments work in different temperature and conditions.

4. As an engineer, I want to use tools and devices to identify and detect the risks so that I can control and manage in the risks in hazzardous environment.

5. As a health professional, I want to ensure that all the health equipments and kits are ready to go so that I can maintain the health of the worker which can be disrupted by different environmental conditions.

6. As a scientist, I want to install and check tracking device in the vehicle so that I can trace the locations of the vehicle and do not lose anhy conection with them.

7. As a scientist, I want to have a proper mode of communication so that I cam link with the outside world and give them regular updates.

8. As a service worker, I want to provide all the basic needs including food and water so that I can keep up the living standard of workers and people staying there.

9. As a skilled worker, I want to maintain the structures and system of the base so that I can control the key parts of the system.

10. As an emergency rescue worker, I want to prepare all the mergency kits and mke people aware about the emergecy exit so that I can prioritise safety of the workers.    


## Use cases 

### Tracking the location of the vehicle

* Goal : To track the location and path of the vehicle
* Primary actor : Driver
* Secondary actor : Trackind device, tracking application, sensor
* Trigger : The vehicle starts to move from its starting point and trackind device is turned on.
* Pre- condition : The tracking device is installed and the user has acces can observe everything through tracking application.
* Flow of events :
                 
                 1. The tracking device is installed and turned on.
                 2. The vehicle starts to move from its initial point.
                 3. The tracking device starts to track and shows all the location of the vehicle.
                 4. The user is able to identify the destination.

* Extensions : The tracking device loses the signal.

                 1. The system waits for the vehicle to move out of the poor signal.
                 2. The system asks the software to be updated.
                 3. Use case resumes. 
                
                
### Monitoring the weather condition

* Goal : To monitor the temperature, ice and wind conditions of the base.
* Primary actor : weather forecasteer, service workers
* Secondary actor : weather station, weather mapping application, devices, instruments
* Trigger : The weather forecaster requests the weather data from weather station hourly.
* Pre-condition : The user has established communication link with weather station and has access to the application.
* Flow of events : 

                  1. The user requests the imformation hourly depending on the circumstances.
                  2. The user gets information every hour.
                  3. The user can access the updates through the mapping application. 
                  4. The user can avoid environmental hazzard with the help of it.
                  
* Extensions: The system shut down suddenly.

                 1. The system asks the osftware to be updated accordinly.
                 2. Use case resumes.
 
 
 ![UML case diagram](https://user-images.githubusercontent.com/83198969/116499515-e9951600-a8de-11eb-804d-c082cae6d75e.png)
                 
                 
## Usability requirements 

1. The tracking device must allow users to trace the location of the vehicle within 5 seconds it is turnes on, on average.

2. The weather station must provide service workers with the information of weather every hour at least 99% of the time.

3. The toold and devices must facilitate users to identify and detect the risks at least 99% of the time.


## Performance requirements 

1. The tools must detect and identify the risks within 10 seconds of any environmental and weather hazzards.

2. The tracking device must be able to process the location of the last 6 months in total.

3. The weather station must be able to send the information within 5 minute even after the changes or updates in the information.


## Reliability requirements 

1. The tracking device shpuld fail tracing locations no more than 0.1% of all times.

2. The instruments must not show more than 1 error in every 1440 hours.

3. The weather station updates should be available 99.99% of the time. 

  

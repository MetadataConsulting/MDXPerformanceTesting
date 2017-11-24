# MDXPerformanceTesting

The Model Catalogue Performance Testing is an automation Framework which is designed to carry out Performance Testing without the need to use Jmeter IDE

## Getting Started
You need a basic knowledge in jmeter. visit this page in Confluence for more information https://metadata.atlassian.net/wiki/spaces/SME/pages/64061441/Jmeter+Documentation


### Prerequisites

```
Install Taurus CI
Add Jmeter and CSV Plugin to your IDE
```

### Taurus Installation
 
Follow the instruction from the link:                                               
https://gettaurus.org/install/Installation/

### Jmeter Installation
Follow the instruction from the link:                                           
http://jmeter.apache.org/usermanual/get-started.html

### Framework Structure
The Jmeter folder contains all the JMeter HTTP(S) Test Script Recorder. For more information regarding Jmeter Script recorder,visit this page in Confluence: https://metadata.atlassian.net/wiki/spaces/SME/pages/64028732/JMeter+HTTP+S+Test+Script+Recorder.          
The resources folder contains all the CSV files that it uses to support the Jmeter Script and the YAML files. For more information regarding Yaml,visit this website https://gettaurus.org/docs/YAMLTutorial/

## Running the tests                                        
* Navigate to the resources folder
* Select a YAML file 
* Open your Terminal  
* Type this command bzt your yaml file 
```
bzt demo.yml
```
Note that a BlazeMeter report will be generated every time you run the test.


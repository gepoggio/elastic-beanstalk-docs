```
###################################################################################################
#### Copyright 2016 Amazon.com, Inc. or its affiliates. All Rights Reserved.
####
#### Licensed under the Apache License, Version 2.0 (the "License"). You may not use this file
#### except in compliance with the License. A copy of the License is located at
####
####     http://aws.amazon.com/apache2.0/
####
#### or in the "license" file accompanying this file. This file is distributed on an "AS IS"
#### BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
#### License for the specific language governing permissions and limitations under the License.
###################################################################################################

###################################################################################################
#### The following files configure your Ruby Passenger Single instance environment to redirect HTTP
#### requests on port 80 to HTTPS on port 443 after you have configured your environment to support
#### HTTPS connections. 
####
####  https-redirect-ruby-passenger.config
####  passenger-standalone.json
####
#### Both files are to be placed inside your .ebextensions folder. Also note the
#### passenger-standalone.json file already contains some of the configuration needed to configure
#### HTTPS on the instance. The full guide to complete the HTTPS configuration on the instance:
####
#### Configure HTTPS for Ruby with Passenger:
####  http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/https-singleinstance-ruby.html#Passenger
###################################################################################################
```

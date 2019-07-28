# Rooks_repo
Repository for codefundo

There will be a frontend web application which will be developed using JavaScript,HTML and CSS.
Code for the smart contract will be written using solidity.We chose ethereum to be the platform.
Finally it would be tested and then the integration of frontend with the blockchain would be done.
We would then deploy the working model on MS Azure.

The layout of our model is as follows,

Initally,The voter approaches the election commission with a request to be able to vote,the EC,checking for the requirements and once the voter has cleared for eligiblity.The EC stores the information of the voter in a highly secure database with credentials like location,Name,age,constituency etc.

It then provides the person with login credentials with a request for the password to be reset immediately.Only after this will the voter account be activated.

On the day actual voting takes place,the voter would be able to login in the appropriate time slot alloted by the EC which should span for about 45 minutes.(a otp will be generated only during this timeslot which has to be used by the voter to cast his vote a 10 min span is setup until which he can choose his candidate,party etc.)

The smart-contract ensures all the verification is done in accordance with the EC's database.Once verified,it is validated and added to the chain.

Finally,all the votes are counted and the stats/results are displayed on the website.

# Getting Started

## Inital Setup

You first need to register your details with the bot do this by running `+setup`. By doing this you agree to our privacy policy. 

## Static Carbon Footprint 

Your static carboon footprint is things that effect your carbon footprint on a yearly basis. This is divided by 365 and added to your daily.
To do this you need to awnser the following questions. 

| Question?                                                    	| Command           	| Answers                                                                  	| Required 	|
|--------------------------------------------------------------	|-------------------	|--------------------------------------------------------------------------	|----------	|
| How many People live in your household?                      	| +sca people       	| ?                                                                        	| Yes      	|
| How much electricity is used in your household?               |  +sca electricity 	| 2000,              3000,        4800,          7000,       ? (kWh)       	| Yes     	|
|                                                              	|                   	| Hall of residence, Small House, Medium House, Large House, Custom        	|          	|
| Does your Electricity come from a Green tariff?              	| +sca green        	| yes, no                                                                  	| Yes      	|
| How much gas is used in your household?                     	|  +sca gas         	| 0,    5000,              12000,       18000,        27000,       ? (kWh) 	| Yes     	|
|                                                              	|                   	| None, Hall of residence, Small House, Medium House, Large House, Custom  	|          	|
| Do you buy local Food?                                       	| +sca food         	| where possible, always, never                                            	| Yes      	|
| How many litres of heating oil is used in your household?    	| +heating_oil      	| ?                                                                        	| No       	|
| How many kilograms of coal is used in your household?        	| +heating_coal     	| ?                                                                        	| No       	|
| How many kilograms of wood is used in your household?        	| +heating_wood     	| ?                                                                        	| No       	|
| How many kilograms of bottled gas is used in your household? 	| +heating_bgas     	| ?                                                                        	| No       	|

## Variable Carbon Footprint

Your variable carbon footprint is things that effect your carboon footprint on a day to day basis. 

| Question?                                                                    	| Command          	| Answers         	| Required 	|
|------------------------------------------------------------------------------	|------------------	|-----------------	|----------	|
| How much of the   food that you eat is organic?                              	| +vca food 1      	| all, some, none 	| Yes      	|
| Did you eat meat today?                                                      	| +vca food 2      	| yes, no         	| Yes      	|
| Did you eat a pre-packaged / processed   meal today?                         	| +vca food 3      	| yes, no         	| Yes      	|
| How much of that food did you waste?                                         	| +vca food 4      	| all, some, none 	| Yes      	|
|                                                                              	|                  	|                 	|          	|
| Did you use the bus today?                                                   	| +vca transport 1 	| ? (Miles)       	| No       	|
| Did you use a train today?                                                   	| +vca transport 2 	| ? (Miles)       	| No       	|
| Did you use a car today? Sports car or   large SUV (35 mpg)                  	| +vca transport 3 	| ? (Miles)       	| No       	|
| Did you use a car today? Small or medium   SUV, or MPV (46 mpg)              	| +vca transport 4 	| ? (Miles)       	| No       	|
| Did you use a car today? City, small,   medium, large or estate car (52 mpg) 	| +vca transport 5 	| ? (Miles)       	| No       	|
| Did you fly by plane today?                                                  	| +vca transport 6 	| ?(Miles)        	| No       	|
|                                                                              	|                  	|                 	|          	|
| How much Money did you spend today?                                          	|                  	|                 	|          	|
| Way Above Average >£200                                                      	| +vca money 1     	|                 	|          	|
| Above average £51 -£200                                                      	| +vca money 2     	|                 	|          	|
| Average £21 - £50                                                            	| +vca money 3     	|                 	|          	|
| Below average £1 - £20                                                       	| +vca money 4     	|                 	|          	|
| None £0                                                                      	| +vca money 5     	|                 	| Yes      	|

# Voices of Mumbai
Often time, we come across various problem on the streets of Mumbai, but we are clueless as to where to report the same. So, this project is to create a portal for the same, where citizens can report their problems, and others can view, vote and comment on the same, with respect to the status of the problem, whether it is resolved, ongoing, or gotten worse. Apart from that, users can mark locations as well on the map, where they encountered the problem.

* Lodging problems and gauge their severity or distance
* Vote, comment and view problems according to severity or distance
* Mark locations on the map, where the problem was faced, extract the ward that problem belongs to, report to the ward

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* Python 3.5.2
* [Telegram Bot](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-4.0)


### Installing

A step by step series of examples that tell you how to get a development environment up and running

##### Install Python-Dependencies
```
pip3 install -r requirement.txt
```
##### Create a local copy 
```
git clone https://github.com/Praneet9/Voices_of_Mumbai.git
```

## Running the Project
* First run the SERVER

```
python app.py
```
* Now add the models and weight to appropriate location
	Download files from below
	```
	https://drive.google.com/drive/folders/1bYrRL5txddOoQlkqrNwD-q0tiXJKXDQM?usp=sharing_eip&ts=5c9791f2
	```

* Add file: training_result.h5 to Final/pothole_classification/
* Add file: full_yolo_backend.h5 to Final/pothole
* Add file: trained_wts.h5 to Final/pothole/weights/

* Now run the telegram bot server

```
python test.py
```
## Testing the Project

#### NOTE
##### For testing the project create your own bot from the [link](https://docs.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-4.0) 
##### And generate api keys (config.json) and add it to Final/api_key

#### Telegram App 
![](Final/tele.gif)

#### Website
![Panel](Final/img1.jpg)
![User](Final/img2.jpg)

## Built With

* [Flask](https://flask.palletsprojects.com/en/1.0.x/) - The web framework used
* [Bootstrap](https://getbootstrap.com) - FrontEnd
* [Telegram](https://telegram.org) - App for conversation with bot

## Authors

* **Praneet Bomma** - [Praneet9](https://github.com/Praneet9)
* **Bhumit Adivarekar** - [AdivarekarBhumit](https://github.com/AdivarekarBhumit)
* **Ganesh Pawar** - [gnasherx](https://github.com/gnasherx)
* **Muteeullah** - [Muteeullah](https://github.com/Muteeullah)
* **Vishal Gawde** - [vrgawde](https://github.com/vrgawde)

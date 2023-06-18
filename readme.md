# Campus Management System Bot

This repository contains the source code for a Campus Management System bot built with Rasa. The bot provides functionality to handle various student requests related to leave applications, grades, class schedules, courses, and attendance.

## Getting Started

### Installation

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/m-aliabbas/campus-management-bot.git

   ```
2. Install the requirments

    ```
    pip install -r requirements.txt
    ```

### Training the Bot

To train the bot, run the following command:

```
rasa train nlu
```
This command will train the NLU models and the dialogue management models based on the data provided in the data directory.
### Running the Bot

```
rasa run -m models/nlu-20230618-025904-mint-canal.tar.gz --enable-api
```

This will start a chat interface where you can interact with the bot and test its functionality.


### Customization

You can customize the bot's behavior by modifying the domain file (domain.yml) and the training data files in the data directory. Add more intents, entities, and responses as per your requirements.

You can also enhance the bot's capabilities by adding more actions and implementing custom logic in the actions.py file.


Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

### License

This project is licensed under the MIT License. See the LICENSE file for details.


Feel free to customize and modify this README file to match your specific project details and requirements.


### Credit:
This project is created by Mohammad Ali Abbas (Sr. ML Engr Idrakai)

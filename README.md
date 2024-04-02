# age-calculator-slackbot
In this repository we build a simple slack bot to calculate age.

# Pre-requsites
- You must have a Slack Workspace and you must be an admin of that.
- If you don't have it, create a new workspace.
- Then go to [https://api.slack.com/apps](https://api.slack.com/apps)
  
  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/1.png)

- Click on **create an app** and select from scratch.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/2.png)

- Enter the name of your app and select the workspace for that app.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/3.png)

- Then go to **socket mode** and click on enable socket mode.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/4.png)

- Enter your token-name and generate the **app token**.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/5.png)

- Copy you app token and save it in a text file to use it later.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/6.png)

- Then go to **event subscriptions**.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/7.png)

- Click on add bot user events.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/8.png)

- Add required bot event subscriptions for the bot.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/9.png)

- Now go to **auth & permissions**

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/10.png)

- click on **add an OAuth Scope** under **Bot Token Scopes** section.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/11.png)

- Give necessary authorization and permission by selecting required OAuth scopes.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/12.png)

- Click on **install to workspace** to install your bot to your workspace.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/13.png)

- After installation, copy your **Bot token** and save it in a text file to use it later.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/15.png)

- Initiate your go project and install the **shomali11/slacker** package by using following commands

  ```
  go mod init github.com/usename/project-name
  go get "github.com/shomali11/slacker"
  ```
  
  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/16.png)

# Running the bot
- Clone the repository.
- Replace **App Token** & **Bot Token** with your tokens.
- Open terminal and run `go build`
- run `go run main.go` and if you the result as shown in picture below, it mean bot is running and connected to slack

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/17.png)

- Open your **Slack Workspace** then open any chat channel and mention the bot and say **"my yob is <year>"**. The bot will give you the age.

  ![](https://github.com/imran1509/age-calculator-slackbot/blob/main/Prerequisite-screenshots/18.png)

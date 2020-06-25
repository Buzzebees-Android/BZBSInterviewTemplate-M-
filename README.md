# BuzzeBees Android Assignment 

## Deadline : (26/06/2020)
## Confidential
Please don't disclose this assignment with anyone. 

## Story and Goals
We plan to launch a privileged app. Your responsibility is to create the project's base structure. It's going to be a long term project so the structure should be flexible, easy to understand, and easy to be supported by your team members.

## Your task

Your task is to create a Buzzebees privileged app. The app has two main pages, Campaign List Page and Details Page. When a user clicks a campaign item, it navigates to the campaign's details page. The details page display the details of the selected campaign from the main page.

## Design

Please refer to this link
```
https://www.figma.com/file/VXpHjgQVYMXSkzKu4Pf5QH/Buzzebees-Android-Test-Level-1?node-id=0%3A1
```
Your final UI can look different from the design, but it should include the same information we provided.

## API details

To get the campaign list, please use
```
GET https://firebasestorage.googleapis.com/v0/b/android-interview-test.appspot.com/o/campaigns.json?alt=media&token=c4aa376e-d07a-49fd-b6d3-a2dd52e9c47f
```

## Code requirements
 * The app must be written in Kotlin only
 * We prefer MVVM architecture, but you can use MVP
 * We prefer to use a dependency injection framework
 * We prefer scalable, maintainable and testable code
 * Having Unit tests would be a plus but not required
 * Having database cache would be a plus but not required
 * **[Bonus]** Using Kotlin Coroutine would be a plus but not required
 * **[Bonus]** Using Koin or Dagger as a dependency injection framework would be a plus but not required
 * **[Bonus]** Having Jetpack Components would be a plus but not required
* **[Bonus]** Having some unit test

## Application requirements

### Campaign List Screen

![List](https://github.com/Buzzebees/BZBSInterviewTemplate2/blob/master/screenshots/Campaigns.png?raw=true)

Display a grid of campaigns. Each item displays an image, name, price using `image_url`, `name`, and `price` respectively.

By clicking a campaign, the app will navigate to Details Screen

### Detail Screen

![Details](https://github.com/Buzzebees/BZBSInterviewTemplate2/blob/master/screenshots/Details%201.png?raw=true)

Display the following details of a campaign

* Image
* Name
* Price
* Description

## Submission process
  You can use this repository while you are developing the app. 
  
  To submit the test assignment please **close the issue "Assignment Done" in "issues" tab**.
  
  We will review the code **only after you close "Assignment Done" issue**.

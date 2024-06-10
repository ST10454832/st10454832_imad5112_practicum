# st10454832_imad5112_practicum
 

MODULE NAME: 

MODULE CODE: 

Introduction to mobile application development 

IMAD5112 

 

STUDENT NAME: Mohammed Aarf Patel. 

STUDENT NUMBER: ST10454832. 

 
GITHUB repository link: 


Purpose and explanation of the application: 

 Purpose of the App 
 
The primary purpose of this app is to provide users with detailed weather information for the week. The app is designed to serve a local weather organization by allowing users to: 
1. View Average Weekly Temperature: Display the average temperature for the entire week. 
2. Access Daily Weather Details: Offer detailed weather information for each day, including minimum and maximum temperatures, and weather conditions. 
3. Navigate Between Screens: Provide smooth navigation between different screens (splash screen, main screen, and detailed view screen). 
4. Input and Manage Data: Allow users to input and clear weather data, ensuring that they can correct any input errors. 
 
Explanation of the App 
 
Splash Screen 
- Purpose: This initial screen serves to welcome the user, displaying the app's name, a logo, and developer information. 
- Elements: 
  - App logo 
  - App name 
  - Developer name 
  - Developer student number 
  - Buttons: Navigate to the main screen or exit the app 
 

Main Screen 
- Purpose: This screen provides an overview of the week's weather and allows navigation to detailed daily views. 
- Elements: 
  - TextViews: Display average temperature for the week 
  - Buttons: 
    - Navigate to the detailed view screen 
    - Clear data input 
    - Exit the app 
  - Daily Buttons: Allow quick navigation to detailed view for each day of the week 
 
Detailed View Screen 
- Purpose: This screen provides detailed weather information for a specific day. 
- Elements: 
  - TextView: Display detailed weather information (min/max temperature and weather condition) for the selected day 
  - Button: Navigate back to the main screen 
 
 Features and Functionality 
 
1. Data Management with Arrays: 
   - Arrays: Store minimum temperatures, maximum temperatures, and weather conditions for each day of the week. 
   -Parallel Arrays: Utilize parallel arrays to keep track of data for each day. 
 
2. Calculate Average Temperature: 
   - Loo: Iterate through the temperature arrays to calculate the average weekly temperature. 
   - Display: Show the average temperature on the main screen. 
 
3. Screen Navigation: 
   - Buttons: Implement buttons to allow users to navigate between screens (main, detailed view, and splash screens). 
   - Back Navigation: Ensure users can easily return to the main screen from the detailed view screen. 
 
4. Error Handling: 
   - Data Validation: Validate user input to ensure data correctness. 
   - Feedback: Provide constructive feedback messages if the user inputs incorrect data. 
 
### User Interaction 
 
1. Launching the App: 
   - User sees the splash screen with the app's logo, name, and developer information. 
   - User can either navigate to the main screen or exit the app. 
 
2. Main Screen Interaction: 
   - User views the average temperature for the week. 
   - User can clear previously input data, re-enter data, or navigate to detailed views for each day. 
 
3. Detailed View Interaction: 
   - User selects a day to view detailed weather information. 
   - User can return to the main screen to view overall weekly information or select another day for details. 
 
Pseudocode: 

SplashScreen: 

Display AppName, DeveloperName, StudentNumber, AppLogo 

Display Button &quot;Start&quot; 

Display Button &quot;Exit&quot; 

  

OnButtonClick &quot;Start&quot;: 

Navigate to MainScreen 

  

OnButtonClick &quot;Exit&quot;: 

ExitApp 

  

MainScreen: 

Display InputField Day 

Display InputField MorningScreenTime 

Display InputField AfternoonScreenTime 

Display InputField ActivityNotes 

Display Button &quot;Save Data&quot; 

Display Button &quot;Clear Data&quot; 

Display Button &quot;Detailed View&quot; 

  

OnButtonClick &quot;Save Data&quot;: 

If InputFields are valid: 

Save Data to ArrayLists 

Show Message &quot;Data Saved&quot; 

Else: 

Show ErrorMessage &quot;Please fill all fields&quot; 

  

OnButtonClick &quot;Clear Data&quot;: 

Clear InputFields 

Show Message &quot;Data Cleared&quot; 

  

OnButtonClick &quot;Detailed View&quot;: 

Navigate to DetailedViewScreen with ArrayLists Data 

  

DetailedViewScreen: 

For each Day in ArrayLists: 

Display Day, MorningScreenTime, AfternoonScreenTime, ActivityNotes 

  

Calculate AverageScreenTime: 

TotalTime = Sum of all MorningScreenTime and AfternoonScreenTime 

AverageScreenTime = TotalTime / NumberOfDays 

  

Display AverageScreenTime 

  

Display Button &quot;Back to Main&quot; 

  

OnButtonClick &quot;Back to Main&quot;: 

Navigate to MainScreen 

 

Screenshot of each screen: 

 

 

 

 

 

 

 

Screenshot of error: 

 

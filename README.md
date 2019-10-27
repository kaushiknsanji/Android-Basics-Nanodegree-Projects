# Udacity Android Basics Nanodegree Projects (WIP)

[Curriculum](https://www.udacity.com/course/android-basics-nanodegree-by-google--nd803) built by Google for aspiring Android Developers who are new to programming, that trains them to acquire the real-world skills and teaches how to build and accelerate their journey towards becoming a professional Android developer.

## Core Curriculum

Consists of lessons, tutorial projects and submission projects that teaches the following parts in detail -
* **User Interface**
	* Explains how to transform any hand-drawn app designs into layouts using the XML markup language, with Views and ViewGroups, which are the building blocks of an Android app's user interface to display images and text.
	* Submission Project-1: [Single Screen App](#1-single-screen-app---invitation)
  
* **User Input**
	* Elaborates on the power of Java through the process of building a coffee-ordering app, using variables to add interactivity to the app, while educating the basics of object-oriented programming.
	* Submission Project-2: [Score Keeper App](#2-score-keeper-app---tennis-scoring)
	* Submission Project-3: [Quiz App](#3-quiz-app---quiz-of-aves)
  
* **Multi-Screen Apps**
	* Explains how to show multiple screens in a Miwok language app, incorporating audio and images to the app, while educating how Android handles touch events. Also, instructs on how to make visual changes in order to polish a fully functional app.
	* Submission Project-4: [Musical Structure](#4-musical-structure---rhythm)
	* Submission Project-5: [Report Card class](#5-report-card-class---report-card-app)
	* Submission Project-6: [Tour Guide App](#6-tour-guide-app---xploremysuru)
  
* **Networking**
	* Elaborates on the power of Web APIs and explains how to use them in apps for learning the basics of networking in Android, including HTTP networking, JSON parsing, and threads.
	* Submission Project-7: [Book Listing App](#7-book-listing-app---books-library)
	* Submission Project-8: [News App](#8-news-app---novalines)
  
* **Data Storage**  
	* Educates about the importance of data persistence when building an Android app. Explains how to work with SQL databases and Content Providers, which helps to keep the app's data bug-free and allows to share an app's data storage with other developers.
	* Submission Project-9: [Habit Tracker App](#9-habit-tracker-app---hydrationtracker)
	* Submission Project-10: [Inventory App](#10-inventory-app---storeapp)
	
---

## Project Submissions

### 1. Single Screen App - [Invitation](https://github.com/kaushiknsanji/Invitation_Udacity_Project)

<image align="right" src="https://github.com/kaushiknsanji/Invitation_Udacity_Project/blob/release_v1.0/app/src/main/ic_launcher-web.png" width="25%"/>

![GitHub](https://img.shields.io/github/license/kaushiknsanji/Invitation_Udacity_Project)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kaushiknsanji/Invitation_Udacity_Project)  ![GitHub repo size](https://img.shields.io/github/repo-size/kaushiknsanji/Invitation_Udacity_Project)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/kaushiknsanji/Invitation_Udacity_Project)](https://github.com/kaushiknsanji/Invitation_Udacity_Project/releases)  ![GitHub All Releases](https://img.shields.io/github/downloads/kaushiknsanji/Invitation_Udacity_Project/total)  ![Minimum API level](https://img.shields.io/badge/API-15+-yellow)

**Invitation** is a Single Screen App that displays details of a particular location of interest which includes "Contact information", " Location Address", "Description of the Business" and "Hours of operation".

#### Topics learnt/explored
* Transforming designs into layouts using `RelativeLayout` and `TableLayout` ViewGroups.
* Usage of `ScrollView`, `TextView`, `ImageView` and designing Dividers using `View`.

#### Sample Screenshots
<img src="https://user-images.githubusercontent.com/26028981/65308112-fdc34e00-dba6-11e9-9756-f7aca785076c.png" width="40%"/>  <img src="https://user-images.githubusercontent.com/26028981/65308124-02880200-dba7-11e9-8899-45b116a1f0b0.png" width="40%"/> 

#### Review from the Reviewer (Udacity)
![Review_Single_Screen_App](https://user-images.githubusercontent.com/26028981/65308168-19c6ef80-dba7-11e9-9d37-0d6c4d878d86.PNG)

### 2. Score Keeper App - [Tennis Scoring](https://github.com/kaushiknsanji/Tennis_Score_Keeper_Udacity)

<image align="right" src="https://github.com/kaushiknsanji/Tennis_Score_Keeper_Udacity/blob/release_v1.0/app/src/main/ic_launcher-web.png" width="25%"/>

![GitHub](https://img.shields.io/github/license/kaushiknsanji/Tennis_Score_Keeper_Udacity)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kaushiknsanji/Tennis_Score_Keeper_Udacity)  ![GitHub repo size](https://img.shields.io/github/repo-size/kaushiknsanji/Tennis_Score_Keeper_Udacity)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/kaushiknsanji/Tennis_Score_Keeper_Udacity)](https://github.com/kaushiknsanji/Tennis_Score_Keeper_Udacity/releases)  ![GitHub All Releases](https://img.shields.io/github/downloads/kaushiknsanji/Tennis_Score_Keeper_Udacity/total)  ![Minimum API level](https://img.shields.io/badge/API-15+-yellow)

**Tennis Scoring** is the Score Keeper App for Tennis, based on the rules followed in the Grand Slams for Men's and Women's Tennis. It has a Single Screen that displays the Scoreboards for the Tennis Match, as well as tracks and manages the scores of each Player during the Play.

#### Topics learnt/explored
* Using `LinearLayout` with weights.
* Registering Buttons with Click listener.
* Usage of App resource values for colors, dimensions, strings and styles.
* Saving the state of Text values shown in `TextView` and `Button`, post configuration change.

#### Sample Screenshots
|Start of the Match|Scoring in a Set|Scoring in a Tie-Breaker|Match Finish|
|---|---|---|---|
|![Initial_Portrait_1](https://user-images.githubusercontent.com/26028981/65620659-d96cd480-dfdf-11e9-9346-9158821351e6.png)|![Intermediate_GamePlay_Score](https://user-images.githubusercontent.com/26028981/65620698-ec7fa480-dfdf-11e9-9294-c50eb9ac1fd6.png)|![Intermediate_TieBreaker_Score](https://user-images.githubusercontent.com/26028981/65620704-ee496800-dfdf-11e9-8b40-947d757558ef.png)|![Match_finish](https://user-images.githubusercontent.com/26028981/65620733-fbfeed80-dfdf-11e9-9098-4597a1a96ad3.png)|

#### Review from the Reviewer (Udacity)
![Review_Score_Keeper_App](https://user-images.githubusercontent.com/26028981/65620779-15a03500-dfe0-11e9-87c8-83821c872914.PNG)

### 3. Quiz App - [Quiz of Aves](https://github.com/kaushiknsanji/Bird_Quiz_App)

<image align="right" src="https://github.com/kaushiknsanji/Bird_Quiz_App/blob/release_v1.0/app/src/main/ic_launcher-web.png" width="25%"/>

![GitHub](https://img.shields.io/github/license/kaushiknsanji/Bird_Quiz_App)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kaushiknsanji/Bird_Quiz_App)  ![GitHub repo size](https://img.shields.io/github/repo-size/kaushiknsanji/Bird_Quiz_App)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/kaushiknsanji/Bird_Quiz_App)](https://github.com/kaushiknsanji/Bird_Quiz_App/releases)  ![GitHub All Releases](https://img.shields.io/github/downloads/kaushiknsanji/Bird_Quiz_App/total)  ![Minimum API level](https://img.shields.io/badge/API-16+-yellow)

**Quiz of Aves** is a Quiz App on **Birds**, that has a total of **50** questions in variety of formats such as "free text response", checkboxes (Multi-choice) and radio buttons (Single-choice). It presents the user with a randomly selected set of questions (read from the String resources) for the number of questions the user wishes to take the quiz, with options for "Multi-choice" and "Single-choice" questions displayed in a random order. For each question, user is presented with an optional Hint after an incorrect attempt, that shows an Image of the Bird(s) in question as a hint when requested by the user to reveal the hint, which in turn means that the user gets a second chance to answer each question. Entire quiz is timed, and the timer value is set accordingly to the number of questions selected by the user, by allocating 45 seconds for each question. The timer runs even when the app goes into background. At the end of the quiz, a dialog will show up for displaying the final score to the user.

#### Topics learnt/explored
* `android.os.AsyncTask` for downloading the images for each of the questions. Headless [`Fragment`](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/java/com/example/kaushiknsanji/birdquiz/ImageDownloaderTaskFragment.java) has been used for managing this Custom `AsyncTask`.
* [`android.util.LruCache`](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/java/com/example/kaushiknsanji/birdquiz/BitmapImageCache.java) for caching the Bitmaps downloaded.
* `android.os.CountDownTimer` for the Quiz Timer. Headless [`Fragment`](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/java/com/example/kaushiknsanji/birdquiz/CountDownLatchFragment.java) has been used for managing the `CountDownTimer`, designed as a latch that adds functionality such as _Pause_ and _Resume_.
* [`DialogFragment`](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/java/com/example/kaushiknsanji/birdquiz/QuestionNumberPickerDialogFragment.java) to display the Number Picker Dialog for the user to select/enter the number of questions to attempt.
* [`DialogFragment`](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/java/com/example/kaushiknsanji/birdquiz/ProgressDialogFragment.java) for displaying the Progress of Image Download, with a custom progress bar layout.
* [`DialogFragment`](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/java/com/example/kaushiknsanji/birdquiz/FinalScoreDialogFragment.java) for displaying the Final score at the end of the quiz or when the quiz timer elapses.
* Intents for moving from one activity to the other.
* [Id resource](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/res/values/ids.xml) for the components generated programmatically.
* Nine patch images used as a background image for the question and option fields.
* [Level List Drawable](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/res/drawable/option_level_list.xml) for decorating the options.
* [State List Drawable](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/res/drawable/button_state_selector.xml) of shape drawables with gradient for the Submit/Hint buttons.
* [String array](https://github.com/kaushiknsanji/Bird_Quiz_App/app/src/main/res/values/quiz_strings.xml) resources for storing the questions, their options and keys.

#### Sample Screenshots
|Welcome Screen|Text input Question|Single-choice Question|Single-choice Question - Correct Answer|
|---|---|---|---|
|![welcome_screen](https://user-images.githubusercontent.com/26028981/27983052-4a1ff1fe-63d1-11e7-913b-d06c095d5001.png)|![textual_question](https://user-images.githubusercontent.com/26028981/27983103-691345a6-63d2-11e7-9ff6-0895d233b813.png)|![mcq_selected_answer](https://user-images.githubusercontent.com/26028981/27983127-dfeea940-63d2-11e7-93d3-478374710a25.png)|![mcq_incorrect_answer](https://user-images.githubusercontent.com/26028981/27983158-6e38f732-63d3-11e7-9ee8-ffc6f55cb97a.png)|

|Multi-choice Question|Multi-choice Question - Correct Answer|Answer Hint|Score on Completion|
|---|---|---|---|
|![mcq_checkbox_selected_answers](https://user-images.githubusercontent.com/26028981/27983163-82ae1b0c-63d3-11e7-9b3e-040d99f3b65d.png)|![mcq_checkbox_incorrect_answer](https://user-images.githubusercontent.com/26028981/27983165-92307bba-63d3-11e7-8bda-3cfc2e8cd0f2.png)|![textual_question_answered_2](https://user-images.githubusercontent.com/26028981/27983110-8d73dafa-63d2-11e7-8918-869415f5dd2f.png)|![score_on_completion](https://user-images.githubusercontent.com/26028981/27983169-a14aace2-63d3-11e7-9539-6c179ccccb3f.png)|

#### Review from the Reviewer (Udacity)
![Review_Quiz_App](https://user-images.githubusercontent.com/26028981/65774028-16a9a180-e15b-11e9-8c83-449bf942946b.PNG)

### 4. Musical Structure - [Rhythm](https://github.com/kaushiknsanji/RhythmApp)

<image align="right" src="https://github.com/kaushiknsanji/RhythmApp/blob/udacity/app/src/main/ic_launcher-web.png" width="25%"/>

![GitHub](https://img.shields.io/github/license/kaushiknsanji/RhythmApp)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kaushiknsanji/RhythmApp)  ![GitHub repo size](https://img.shields.io/github/repo-size/kaushiknsanji/RhythmApp)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/kaushiknsanji/RhythmApp)](https://github.com/kaushiknsanji/RhythmApp/releases)  ![GitHub All Releases](https://img.shields.io/github/downloads/kaushiknsanji/RhythmApp/total)  ![Minimum API level](https://img.shields.io/badge/API-15+-yellow)

**Rhythm** App is a Musical Structure App that showcases a structure/approach typically used for Apps that play music, without implementing its functionality. Each screen in the App displays a Text describing about the screen and what functionality goes into it. Mocking or adding real content is not allowed as per the Project Rubric. Static data from resources are only allowed. As mock up is not allowed, `AdapterView`s and `RecyclerView`s are not used. This enables more practice with using layouts. Hence, the Project mainly focuses on App designing. 

#### Topics learnt/explored
* Fiddled with `CoordinatorLayout` along with `CollapsibleToolbar` and `DrawerLayout`.
* Used `ConstraintLayout` heavily for most of the layouts along with custom `styles`.
* Created a custom [WindowInsetsFrameLayout](https://github.com/kaushiknsanji/RhythmApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/rhythm/extensions/WindowInsetsFrameLayout.java) for dispatching the Window insets from the DrawerLayout to the Fragments shown in this FrameLayout's container, when its `FitSystemWindows` property is set.
* Implemented Base class architecture for abstracting the common tasks to be executed by Activities and Fragments. 
* Persistent Bottom Player is shown in many Fragments and Activities. [PlayerActivity](https://github.com/kaushiknsanji/RhythmApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/rhythm/ui/common/activities/PlayerActivity.java) and [PlayerFragment](https://github.com/kaushiknsanji/RhythmApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/rhythm/ui/common/fragments/PlayerFragment.java) extends the Base classes for Activities and Fragments respectively to abstract the implementation details of the persistent `Bottom Sheet`.
* Common tasks of the Drawer Fragments shown in the `HomeActivity` are abstracted by [DrawerFragment](https://github.com/kaushiknsanji/RhythmApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/rhythm/ui/common/fragments/DrawerFragment.java) abstract class that extends the `PlayerFragment` abstract class, as they also need to show the Persistent Bottom Player.
* Music Player controls are simulated by using a Bound Service [PlayerService](https://github.com/kaushiknsanji/RhythmApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/rhythm/ui/common/services/PlayerService.java). It provides the necessary Play/Pause/Restart methods to control the Player progress value generated by an Internal Worker Thread.
* Implemented a custom `AppBarLayout` [Behavior](https://github.com/kaushiknsanji/RhythmApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/rhythm/extensions/BottomSheetAwareAppBarBehavior.java) to control the Nested scroll events on Layouts with Bottom Sheets, to prevent the scroll from being consumed by the Layout behind the Bottom Sheet when a scroll event occurs on the Expanded Bottom Sheet.
* Implemented a custom `FloatingActionButton` [Behavior](https://github.com/kaushiknsanji/RhythmApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/rhythm/extensions/ScrollAwareAnchoredFabBehavior.java) to control the visibility and appearance of the `FloatingActionButton` when anchored to views other than `AppBarLayout` or views with `BottomSheetBehavior`, as these are taken care by default.
* Implemented a [BottomSheetDialogFragment](https://github.com/kaushiknsanji/RhythmApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/rhythm/ui/jukebox/JukeboxDetailPaymentDialogFragment.java) to show a dialog appearing from the Bottom, to capture the Payment when the user tries to play a song from any of the Jukebox services, to simulate the Paid service.
* Used Animated Vector Drawables for transitioning between "Play-Pause" and "Like-Unlike" drawables through animations.

#### Sample Screenshots

|Drawer|Home|Bottom Sheet Player|Songs|
|---|---|---|---|
|![Drawer](https://github.com/kaushiknsanji/RhythmApp/raw/udacity/art/screenshots/home_drawer.png)|![Home](https://github.com/kaushiknsanji/RhythmApp/raw/udacity/art/screenshots/home_1.png)|![Bottom_Sheet_Player](https://github.com/kaushiknsanji/RhythmApp/raw/udacity/art/screenshots/bottom_sheet_player_1.png)|![Songs](https://github.com/kaushiknsanji/RhythmApp/raw/udacity/art/screenshots/song_list_1.png)|

|Albums|Album Detail|Artists|Artist Detail|
|---|---|---|---|
|![Albums](https://github.com/kaushiknsanji/RhythmApp/raw/udacity/art/screenshots/album_1.png)|![Album_Detail](https://github.com/kaushiknsanji/RhythmApp/raw/udacity/art/screenshots/album_detail_1.png)|![Artists](https://github.com/kaushiknsanji/RhythmApp/raw/udacity/art/screenshots/artist_1.png)|![Artist_Detail](https://github.com/kaushiknsanji/RhythmApp/raw/udacity/art/screenshots/artist_detail_1.png)|
 
#### Review from the Reviewer (Udacity)

![Review_Musical_Structure](https://github.com/kaushiknsanji/RhythmApp/raw/udacity/art/review/review_musical_structure.png)

### 5. Report Card class - [Report Card App](https://github.com/kaushiknsanji/Report_Card_App)

![GitHub](https://img.shields.io/github/license/kaushiknsanji/Report_Card_App)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kaushiknsanji/Report_Card_App)  ![GitHub repo size](https://img.shields.io/github/repo-size/kaushiknsanji/Report_Card_App)  ![Minimum API level](https://img.shields.io/badge/API-15+-yellow)

**Report Card** App is an exercise project aimed at learning how to create and interact with custom Java classes. As such, it is just a Java class, rather than a full Android App. This project has no UI components. It contains only a Model Class [ReportCard](https://github.com/kaushiknsanji/Report_Card_App/blob/udacity/app/src/main/java/com/example/kaushiknsanji/reportcardpojo/models/ReportCard.java) that helps in managing and recording a student’s grades for a particular year.

#### Topics learnt
* Designing a custom POJO/Model class.
* Creating the POJO/Model class in Java code.
* Storing information in a collection and reading the same.

#### Review from the Reviewer (Udacity)

![Review_Report_Card_App](https://github.com/kaushiknsanji/Report_Card_App/raw/udacity/art/review/review_report_card_app.png)

### 6. Tour Guide App - [XploreMysuru](https://github.com/kaushiknsanji/XploreMysuru)

<image align="right" src="https://github.com/kaushiknsanji/XploreMysuru/blob/udacity/app/src/main/ic_launcher-web.png" width="25%"/>

![GitHub](https://img.shields.io/github/license/kaushiknsanji/XploreMysuru)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kaushiknsanji/XploreMysuru)  ![GitHub repo size](https://img.shields.io/github/repo-size/kaushiknsanji/XploreMysuru)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/kaushiknsanji/XploreMysuru)](https://github.com/kaushiknsanji/XploreMysuru/releases)  ![GitHub All Releases](https://img.shields.io/github/downloads/kaushiknsanji/XploreMysuru/total)  ![Minimum API level](https://img.shields.io/badge/API-15+-yellow)

**XploreMysuru** App is a Tour Guide App that guides a user in exploring the **"City of Palaces"/"Mysore"**. It contains 5 lists of relevant attractions comprising of **Places**, **Parks**, **Hotels**, **Restaurants** and **Shops**, presented with `BottomNavigationView` for easier navigation between the lists. All the information (including pictures) for each of the attractions are stored locally and read from App resources.

#### Topics learnt/explored

* Used `ConstraintLayout` heavily for most of the layouts along with custom `styles`.
* Implemented **MVP + Repository** pattern with App Resources.
* Explored `BottomNavigationView` for Navigating between the lists of attraction.
* Implemented [Snap Behavior](https://github.com/kaushiknsanji/XploreMysuru/blob/udacity/app/src/main/java/com/example/kaushiknsanji/xploremysuru/extensions/BottomNavigationBehavior.java) for `BottomNavigationView` that hides the `BottomNavigationView` when more than or equal to half of its height is translated away. The Behavior also takes care of docking the Snackbar on top of the `BottomNavigationView` when shown.
* Used `CardView` for displaying each place of attraction.
* Implemented Loading of Images in a background thread through a Headless [Fragment](https://github.com/kaushiknsanji/XploreMysuru/blob/udacity/app/src/main/java/com/example/kaushiknsanji/xploremysuru/workers/ImageDecoderFragment.java).
* Developed [BitmapImageCache](https://github.com/kaushiknsanji/XploreMysuru/blob/udacity/app/src/main/java/com/example/kaushiknsanji/xploremysuru/cache/BitmapImageCache.java) utility that uses `android.util.LruCache` to cache the recent Bitmap Images decoded. 
* Carried out Image decoding in a background thread using [ImageDecoder](https://github.com/kaushiknsanji/XploreMysuru/blob/udacity/app/src/main/java/com/example/kaushiknsanji/xploremysuru/workers/ImageDecoder.java) that extends `AsyncTaskLoader`.
* Developed [BitmapUtility](https://github.com/kaushiknsanji/XploreMysuru/blob/udacity/app/src/main/java/com/example/kaushiknsanji/xploremysuru/utils/BitmapUtility.java) to extract `Palette` Swatches from the Images.

#### Sample Screenshots

|Places|Hotels|Restaurants (Expanded Item)|BottomNavigationView (Docked Snackbar)|
|---|---|---|---|
|![place_portrait](https://user-images.githubusercontent.com/26028981/51127857-8fc2cc00-184c-11e9-996d-0946ab3ffb2b.png)|![hotel_portrait](https://user-images.githubusercontent.com/26028981/51127897-a49f5f80-184c-11e9-8876-e79b9c4a3101.png)|![restaurant_item_expand](https://user-images.githubusercontent.com/26028981/51127914-ae28c780-184c-11e9-840b-ded292b0d5df.png)|![shop_no_link_2](https://user-images.githubusercontent.com/26028981/51127966-ca2c6900-184c-11e9-9438-7034df166b94.png)|

#### Review from the Reviewer (Udacity)

![Review_Tour_Guide_App](https://user-images.githubusercontent.com/26028981/51263273-edd0ea00-19d9-11e9-837c-7ceb4aefb8c0.png)

### 7. Book Listing App - [Books Library](https://github.com/kaushiknsanji/Books_Library_App)

<image align="right" src="https://github.com/kaushiknsanji/Books_Library_App/blob/udacity/app/src/main/ic_launcher-web.png" width="25%"/>

![GitHub](https://img.shields.io/github/license/kaushiknsanji/Books_Library_App)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kaushiknsanji/Books_Library_App)  ![GitHub repo size](https://img.shields.io/github/repo-size/kaushiknsanji/Books_Library_App)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/kaushiknsanji/Books_Library_App)](https://github.com/kaushiknsanji/Books_Library_App/releases)  ![GitHub All Releases](https://img.shields.io/github/downloads/kaushiknsanji/Books_Library_App/total)  ![Minimum API level](https://img.shields.io/badge/API-15+-yellow)

**Books Library** App is a Book Listing App that connects to the [Google Books API](https://developers.google.com/books/) to retrieve the list of Books for the topic searched and then displays them in a decorative BookShelf format. Provides users the ability to control the Search Results through the various API supported parameters, provided in the Search Settings of the App. The Search box features the API supported search keyword filtering which narrows down the results to the keyword being looked up.

#### Topics learnt/explored

* Assisted Search Implementation with `SearchView`.
* Used `RecyclerView` in place of `ListView` and `GridView` for its advantages in performance and easy placeholders for custom item decoration.
* Custom [RecyclerView.ItemDecoration](https://github.com/kaushiknsanji/Books_Library_App/blob/0c15b06877ca29523a588b67f30431f4acfaed37/app/src/main/java/com/example/kaushiknsanji/bookslibrary/adapterviews/RecyclerViewFragment.java#L362-L445) for decorating each of the items in List/Grid with the Book shelf decoration.
* Explored [FragmentStatePagerAdapter](https://github.com/kaushiknsanji/Books_Library_App/blob/udacity/app/src/main/java/com/example/kaushiknsanji/bookslibrary/adapters/DisplayPagerAdapter.java) that displays the Fragments \(retaining their state\) for the `ViewPager`.
* Implemented `android.support.v7.preference.Preference` Preferences for the Settings.
* No external libraries are used for communicating with the REST API and also for loading the images. `AsyncTaskLoader` has been used for downloading the data and images in the background thread. Images are downloaded using a Headless [Fragment](https://github.com/kaushiknsanji/Books_Library_App/blob/udacity/app/src/main/java/com/example/kaushiknsanji/bookslibrary/workers/ImageDownloader.java).
* Developed [BitmapImageCache](https://github.com/kaushiknsanji/Books_Library_App/blob/udacity/app/src/main/java/com/example/kaushiknsanji/bookslibrary/cache/BitmapImageCache.java) utility that uses `android.util.LruCache` to cache the recent Bitmap Images downloaded. 
* Most layouts are designed using `ConstraintLayout` to flatten the layout hierachy as far as possible.
* Indeterminate progress bar is implemented with animation-list / AnimationDrawable.
* [TextAppearanceUtility](/app/src/main/java/com/example/kaushiknsanji/bookslibrary/utils/TextAppearanceUtility.java) for decorating `TextViews` using Spannables, for strikethrough, image within text, selective text coloring and relative text resize.
* `CardView` for displaying the information of a Book.

#### Video Preview

[![Video of Complete App Flow](https://i.ytimg.com/vi/deXm1yzqRmU/maxresdefault.jpg)](https://youtu.be/deXm1yzqRmU)

#### Sample Screenshots

|Search Screen|Recent Search Suggestions|Results - List|Results - Grid|
|---|---|---|---|
|![welcome_page](https://user-images.githubusercontent.com/26028981/32066973-292b2430-ba9f-11e7-8650-096d1d818fb0.png)|![assisted_search](https://user-images.githubusercontent.com/26028981/32066984-36ffac5c-ba9f-11e7-9698-575374ee48ca.png)|![list_view](https://user-images.githubusercontent.com/26028981/32067013-51ad2cf0-ba9f-11e7-9d75-acec8788c4ed.png)|![grid_view](https://user-images.githubusercontent.com/26028981/32067015-52eeab34-ba9f-11e7-846f-08eb83a8a1bd.png)|

|Book Details - 1|Book Details - 2|Book Image|Settings|
|---|---|---|---|
|![details_portrait_1](https://user-images.githubusercontent.com/26028981/32067039-616fb482-ba9f-11e7-9afc-598898c59640.png)|![details_portrait_2](https://user-images.githubusercontent.com/26028981/32067041-62717ef6-ba9f-11e7-8e36-6b20f02ff66f.png)|![book_image_view](https://user-images.githubusercontent.com/26028981/32067050-68559410-ba9f-11e7-9250-c19f23cf3762.png)|![search_settings](https://user-images.githubusercontent.com/26028981/32067053-6ddcc7aa-ba9f-11e7-9d56-454123d40f64.png)|

#### Review from the Reviewer (Udacity)

![Review_Book_Listing_App](https://user-images.githubusercontent.com/26028981/66827627-b7c29580-ef6c-11e9-9ff5-462488f109fa.PNG)

### 8. News App - [NovaLines](https://github.com/kaushiknsanji/NovaLines_TheGuardianNewsApp)

<image align="right" src="https://github.com/kaushiknsanji/NovaLines_TheGuardianNewsApp/blob/udacity/app/src/main/ic_launcher-web.png" width="25%"/>

![GitHub](https://img.shields.io/github/license/kaushiknsanji/NovaLines_TheGuardianNewsApp)  ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/kaushiknsanji/NovaLines_TheGuardianNewsApp)  ![GitHub repo size](https://img.shields.io/github/repo-size/kaushiknsanji/NovaLines_TheGuardianNewsApp)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/kaushiknsanji/NovaLines_TheGuardianNewsApp)](https://github.com/kaushiknsanji/NovaLines_TheGuardianNewsApp/releases)  ![GitHub All Releases](https://img.shields.io/github/downloads/kaushiknsanji/NovaLines_TheGuardianNewsApp/total)  ![Minimum API level](https://img.shields.io/badge/API-15+-yellow)

**Novalines** App is a News App that connects to the [Guardian News API](https://open-platform.theguardian.com/documentation/) to retrieve the News Feed based on a particular endpoint and then displays them as a list. It implements the **"section"** and **"search"** endpoints. By default, the App loads **"Top Stories"**, **"Most Visited"** and **"World news"** sections. It parses the News Feed for the subscribed News section or the searched News, and then displays the list of News Articles in Cards. On top of these News Articles, many useful features are provided, like -
* Sharing the News Articles.
* Saving the News Article to Bookmarks for Reading later (Stub only).
* Saving the News Articles to Favorites (Stub only).
* Jumping to a particular News section /or temporarily subscribing to a News section.

#### Topics learnt/explored

* Used `RecyclerView` in place of `ListView` (to display the News stories) for its advantages in performance and easy placeholders for custom item decoration.
* Custom [RecyclerView.ItemDecoration](https://github.com/kaushiknsanji/NovaLines_TheGuardianNewsApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/novalines/utils/RecyclerViewItemDecorUtility.java) for adding space between the News List items.
* `CardView` for displaying the News stories content for each News List items.
* Custom Navigation Drawer Items implemented using `RecyclerView`.
* Explored [FragmentStatePagerAdapter](https://github.com/kaushiknsanji/NovaLines_TheGuardianNewsApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/novalines/adapters/HeadlinesPagerAdapter.java) that displays the Fragments \(retaining their state\) for the `ViewPager`. Also, mocks the dynamic adding of additional tab content to the `ViewPager`.
* Implemented Settings using `android.support.v7.preference.Preference`.
* No external libraries are used for communicating with the REST API and also for loading the images. `AsyncTaskLoader` has been used for downloading the data and images in the background thread. Images are downloaded using a Headless [Fragment](https://github.com/kaushiknsanji/NovaLines_TheGuardianNewsApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/novalines/workers/ImageDownloaderFragment.java).
* Developed [BitmapImageCache](https://github.com/kaushiknsanji/NovaLines_TheGuardianNewsApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/novalines/cache/BitmapImageCache.java) utility that uses `android.util.LruCache` to cache the recent Bitmap Images downloaded.
* Most layouts are designed using `ConstraintLayout` to flatten the layout hierarchy as far as possible.
* [TextAppearanceUtility](https://github.com/kaushiknsanji/NovaLines_TheGuardianNewsApp/blob/udacity/app/src/main/java/com/example/kaushiknsanji/novalines/utils/TextAppearanceUtility.java) for decorating `TextViews` using Spannables, for image within text and html content in text.
* Custom Fonts for `TextViews` using `ResourceCompat`.
* Explored `CoordinatorLayout`.
* Used `RecyclerView` in a `SwipeRefreshLayout` to use the integrated Progress/Refresh indicator.
* Used `DiffUtil` in `RecyclerView` to help rebind only the item views that have changed.

#### Video Preview

[![Video of Complete App Flow](https://i.ytimg.com/vi/XzZbe7aYeXU/maxresdefault.jpg)](https://youtu.be/XzZbe7aYeXU)

#### Sample Screenshots

|Drawer|Highlights|Most Visited (with News Item Popup Menu)|Settings|
|---|---|---|---|
|![drawer_layout](https://user-images.githubusercontent.com/26028981/38467585-7f1d3cf4-3b58-11e8-9c4a-988f7f68faa3.png)|![headlines_fragment](https://user-images.githubusercontent.com/26028981/38467590-97648cc2-3b58-11e8-8913-fb3011d00760.png)|![card_item_popup](https://user-images.githubusercontent.com/26028981/38467660-7e924670-3b59-11e8-92bf-8a5321428d80.png)|![settings_screen](https://user-images.githubusercontent.com/26028981/38467697-cfb82272-3b59-11e8-81f5-07e9a7a85326.png)|

#### Review from the Reviewer (Udacity)

![review](https://user-images.githubusercontent.com/26028981/38767016-63bfb7b2-3ff8-11e8-86cf-2930a6fc14fc.PNG)

### 9. Habit Tracker App - [HydrationTracker](https://github.com/kaushiknsanji/HydrationTracker_Demo_App) 

### 10. Inventory App - [StoreApp](https://github.com/kaushiknsanji/StoreApp)

---

## Certificate of Completion

<a href="https://confirm.udacity.com/ERJHK3CF">
<img alt="Udacity Android Basics Nanodegree Certificate" src="https://s3-us-west-2.amazonaws.com/udacity-printer/production/certificates/8708f357-3c02-42df-8ec9-72d03e1057c7.svg" width="50%"/>
</a>

---

## License

```
Copyright 2019 Kaushik N. Sanji

Licensed under the Apache License, Version 2.0 (the "License"); 
you may not use this file except in compliance with the License. 
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0
   
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

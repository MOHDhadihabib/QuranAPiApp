---
Quran Project Documentation

Project Overview

Quran Project is a web application built with Laravel and the Al Quran API. It allows users to access the full Quran, read each Surah, and listen to a complete audio clip for each chapter. The app includes an indexed list of Surahs, a reading view, and audio playback functionality to enhance the user experience.
---

Table of Contents

1. [Project Demo Video](project-demo-video)
2. [Installation and Setup](installation-and-setup)
3. [Tech Stack](tech-stack)
4. [APIs Used](apis-used)
5. [Features and Functionalities](features-and-functionalities)
6. [Usage](usage)
7. [Contributing](contributing)

---

1.  Project Demo Video

You can view a demonstration of the Quran Project in action at the following link:

[Project Demo Video](https://github.com/user-attachments/assets/21df6235-28fd-4e38-ae34-91fba88d52b4)

---

2.  Installation and Setup

Prerequisites

-   PHP >= 7.3
-   Composer
-   MySQL
-   Laravel Framework >= 8.x

Steps

1. Clone the Repository

    ```bash
    git clone <repository-url>
    cd Quran-Project
    ```

2. Install Dependencies

    ```bash
    composer install
    ```

3. Start the Server

    ```bash
    php artisan serve
    ```

    - Your application should now be running at `http://localhost:8000`.

---

3.  Tech Stack

-   Backend: Laravel (PHP Framework)
-   Frontend: Blade templates, HTML, CSS, JavaScript
-   API Integration: Al Quran API
-   Database: MySQL
-   Package Management: Composer (PHP)

---

4.  APIs Used

-   Al Quran API: This API provides Quranic content, including:
    -   Surah names and indexes
    -   Full Surah text content
    -   Audio files for each Surah

---

5.  Features and Functionalities

Surah Index

-   Functionality: Displays a list of all Surahs with names and Surah numbers.
-   Implementation: Rendered using `index.blade.php` with data from the Al Quran API.

Read Full Surah

-   Functionality: Allows users to read the full text of any selected Surah.
-   Implementation: The Surah content is fetched using the API and displayed in `surah.blade.php`.

Audio Playback

-   Functionality: Provides an audio clip for each Surah so users can listen while they read.
-   Implementation: The audio link is retrieved from the API and embedded using HTML5 audio controls.

---

6. Usage

1. Viewing the Surah List

    - Go to the homepage to see the list of Surahs.
    - Click on any Surah to view its full content and listen to the audio.

1. Reading and Listening to a Surah
    - Click on a Surah to open it in a full view.
    - Use the "Play Audio" button to listen to the Surah while reading.

---

7.  Contributing

To contribute:

1. Fork the repository and clone it locally.
2. Create a new branch for your feature or bug fix.
3. Push to your branch and create a pull request.

---

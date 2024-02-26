# STREcording
<div align=center>
<img width="100%" alt="제목 없음" src="https://github.com/Solution-Challenge-stress-solution/.github/assets/129071350/55db613e-18e9-4ca0-b50b-5da99c3fa135">
<br>
</div>

<br>

## 🔥 Motivation

Mental health has become a significant concern in Korea. According to SBS News, the number of depression patients in Korea exceeded 1 million in 2022, and in KBS News, one in four elementary, middle, and high school students are considering extreme choices like suicide due to academic stress. 

The highly competitive nature of Korean society contributes to a widespread experience of burnout syndrome among young students to adults. Because of the social atmosphere that considers enduring to be a virtue,  many individuals do not even recognize their feelings and stress accurately.

As mental health has become a serious concern in Korean society, we felt the need for an app that could present people’s emotions and stress with precise indexes and manage them.

<br>

## ⛳ Targeted UN SDG

<img width="193" alt="image" src="https://github.com/Solution-Challenge-stress-solution/.github/assets/129071350/bcaf588f-4149-4035-addc-7e287febb1f4">

<br><br>

## 🎙️ What is STREcording?

STREcording offers a unique solution, allowing users to record and analyze their emotions through voice diaries and providing accurate stress levels and activity recommendations to foster psychological well-being and promote a healthier lifestyle.

<br>

## 💻 Tech Stack

### FrontEnd

![Flutter](https://github.com/Solution-Challenge-stress-solution/.github/assets/66584938/b7e64be6-19b9-4c9e-9f2b-77219dd44dfa)

### BackEnd

![GCP](https://github.com/Solution-Challenge-stress-solution/.github/assets/66584938/49b04f73-ac5b-4574-8728-f486cd82960d)
![Spring Boot](https://github.com/Solution-Challenge-stress-solution/.github/assets/66584938/5103020c-03e3-4d64-b9b4-b03eb1daaee5)
![MySQL](https://github.com/Solution-Challenge-stress-solution/.github/assets/66584938/a4a11ea5-f18e-4f0a-bca1-30a432653e2b)
![JWT](https://github.com/Solution-Challenge-stress-solution/.github/assets/66584938/c38af486-fe33-4119-89df-8bee5d88bf29)

- GCP: `Google Compute Engine`, `Google Cloud Storage`, `Google Cloud SQL`, `Google Cloud Speech-to-Text`, `Google Cloud Run`
- Spring: `Spring Boot`, `Spring Data JPA`, `Spring Security`

### Machine Learning

![Colab](https://github.com/Solution-Challenge-stress-solution/.github/assets/66584938/dd32f06b-df90-4a9e-9547-d16bfa0c8013)

- ML Model: `Tesorflow`, `Keras`, `Scikit-learn`, `librosa`, `Numpy`, `Pandas`, `Seaborn` etc.

### DevOps
![Docker](https://github.com/Solution-Challenge-stress-solution/.github/assets/66584938/2270999b-f858-4a52-9a39-fca37ee64d8c)

<br>

## 🛠️ System Architecture

<img width="635" alt="image" src="https://github.com/Solution-Challenge-stress-solution/.github/assets/129071350/6cbecece-5d4e-4fa9-8011-ed1c3e64880c">

<br><br>

## 📲 Execution Method

### For Android User 

Download apk file [here](https://drive.google.com/file/d/1QBPUaDKrCEAQaf-QMJJIxq3ohxxGSQ9L/view?usp=drive_link)!

## 🏃‍♀️ How to Run

### Getting Started

To get a local copy up and running follow these simple steps.

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Prerequisites

Before running this project, you need to have Flutter installed on your machine. If you don't have Flutter SDK installed, please visit the [official Flutter installation guide](https://flutter.dev/docs/get-started/install).

### Installation

1. Clone the repository
   ```
   git clone https://github.com/Solution-Challenge-stress-solution/FrontEnd.git
   ```
2. Navigate to the directory
   ```
   cd FrontEnd
   ```
### Runing the application
1. Get Flutter packages
   ```
   flutter pub get
   ```
2. Run the app on an emulator or physical device
   ```
   flutter run
   ```

<br>

## 🛠️Deployment Process (CI/CD using Github Actions)

### Local : Gradle build, Docker build
1. Build jar : `gradle build` or `gradlew build`
2. Build Docker Image : `docker build -t yourAccountName/repositoryName ./`
3. Push to Docker Hub : `docker push yourAccountName/repositoryName`

### Server : Deploy
1. Pull from Docker Hub : `docker pull yourAccountName/repositoryName`
2. Run Docker Image : `docker run -d -p 8080:8080 yourAccountName/repositoryName`

(`AccountName` and `RepositoryName` are from Docker Hub)


<br>


## 🎬Demo Video
[![STRecording](http://img.youtube.com/vi/tU19RDkrfUk/0.jpg)](https://www.youtube.com/watch?v=tU19RDkrfUk&t=0s) 

<br>

## 📜API Docs

👉🏻[STRecording Swagger](http://strecording.shop:8080/swagger-ui/index.html#/) 

<br><br>

## 🔍ERD

<img width="479" alt="image" src="https://github.com/Solution-Challenge-stress-solution/.github/assets/59828706/986eb343-5ee9-4db1-a479-433075db80a6">

👉🏻[ERDCloud](https://www.erdcloud.com/d/ca8giPxrfJzhiijus) 

<br>

## 📑Convention

### 1) Commit Convention

| Tag name | Description                                                 |
| -------- | ----------------------------------------------------------- |
| feat     | Commits that add a new feature                              |
| fix      | Commits that fix a bug                                      |
| hotfix   | Fix an urgent bug in issue or QA                            |
| build    | Commits that affect build components                        |
| chore    | Miscellaneous commits                                       |
| style    | Commits for code styling or format                          |
| docs     | Commits that affect documentation only                      |
| test     | Commits that add missing tests or correcting existing tests |
| refactor | Commits for code refactoring                                |

### 2) Coding Convention

- Variables, functions, and class names should use camelCase.
- For functions, use a verb followed by a noun.
- Column names stored in the DB should use snake_case.
- URL names should use kebab-case, consisting of lowercase nouns.
- Use hyphens (-) as separators, and avoid using separators when possible.

<br>

## 👨‍👩‍👧‍👦 Contributors

|                                  Frontend                                   |                                    Backend                                   |                                   Backend/ML                                    |                                    Backend                                     |
| :--------------------------------------------------------------------------: | :---------------------------------------------------------------------------: | :--------------------------------------------------------------------------: | :---------------------------------------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/66584938?v=4" width=150px> | <img src="https://avatars.githubusercontent.com/u/59828706?v=4" width=150px> | <img src="https://avatars.githubusercontent.com/u/105757703?v=4" width=150px> | <img src="https://avatars.githubusercontent.com/u/129071350?v=4" width=150px> |
|                     [이정현](https://github.com/JHyeon0915)                     |                     [고경남](https://github.com/rhrudska987)                     |                   [박정준](https://github.com/prislewarz)                   |                   [이지원](https://github.com/orieasy1)                   |


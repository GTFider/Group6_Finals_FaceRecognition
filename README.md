## 𝐆𝐫𝐨𝐮𝐩6_𝐅𝐢𝐧𝐚𝐥𝐬_𝐅𝐚𝐜𝐞𝐑𝐞𝐜𝐨𝐠𝐧𝐢𝐭𝐢𝐨𝐧
![NBA Logo](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/23686a19-e89b-4a8e-918a-fb19adf068a9)

Thirty clubs compete in the professional basketball competition known as the National Basketball Association (NBA), which is split into the Eastern and Western conferences. Since its founding in 1946, the NBA has grown to be one of the world's most well-liked and fiercely contested basketball leagues. Teams in the league compete for postseason places based on their win-loss records throughout the regular season, which normally runs from October to April. The NBA Finals, which take place in June, decide who wins the league. Notable players in the league's illustrious history include Michael Jordan, LeBron James, and Kobe Bryant. The NBA is well-known for its elite athletes, talented players, and large international fan base.

For the given task, the group was assigned to develop a face recognition program that can identify both unknown and known faces. In alignment with the previous activity during the midterms, where the group created a dashboard about LeBron James' NBA Stats, the group will use Google Colab to identify the faces of the players of their choice, as well as their faces when they are with their other teammates.

## NBA PLAYERS
_The following NBA Players were used for the Face Recognition:_

## Stephen Curry 🌟
![Steph GIF](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/c03138b2-de78-4409-91f4-9ce0b8342100)

Professional basketball player **Stephen Curry** has spent his whole playing career in the NBA with the Golden State Warriors. Curry, who was born in Akron, Ohio, on March 14, 1988, is recognized as one of the best shooters in sports history. Playing as a point guard, he stands 6 feet 3 inches (1.91 meters) tall and has helped the Warriors win numerous NBA titles. In addition to winning two NBA Most Valuable Player (MVP) awards, Curry has broken other three-point shooting records, including the record for most three-pointers made in a single season. In addition to his accomplishments on the floor, Curry is renowned for his charitable endeavors and good influence off the court.

## Giannis Antetokoumnpo 🌟
![Giannis GIF](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/4140d3a1-86a8-488a-b474-9e572aab588f)

Greek-born professional basketball player **Giannis Antetokounmpo** was born on December 6, 1994, and he currently plays for the Milwaukee Bucks in the NBA. Reaching a height of 2.11 meters (6 feet 11 inches), he is renowned for his remarkable athleticism, adaptability, and distinct skill set. Known as the "Greek Freak," Giannis has been named the NBA Most Valuable Player (MVP) on several occasions. In 2021, he led the Bucks to an NBA title and was named the MVP of the NBA Finals. His style of play blends skillful defensive play, explosive dunks, and versatility on the floor. Outside of the court, Giannis is praised throughout Greece and the US for his charitable endeavors, work ethic, and humility.

## Luka Dončić 🌟
![Luka GIF](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/d559722e-f410-4505-bd65-1514c25260b5)

Slovenian professional basketball player **Luka Dončić** was born on February 28, 1999, and he currently plays for the Dallas Mavericks in the NBA. Dončić, who is well-known for his extraordinary abilities, basketball intelligence, and vision, made a big impression on the league at an early age. With a height of 2.01 meters, or 6 feet 7 inches, he mainly plays forward and guard. After winning the 2019 NBA Rookie of the Year award, Luka went on to be picked as an NBA All-Star twice. Dončić's play style is characterized by his remarkable ball-handling skills, scoring prowess, and remarkable ability to produce clutch plays. Off the court, he is well-known for his warm demeanor and universal appeal, which helps the NBA's expanding foreign membership.

## Nikola Jokić 🌟
![Jokic GIF](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/1251d679-55dc-4b0f-9b5f-ebfb23e4f774)

Born on February 19, 1995, **Nikola Jokić** is a Serbian professional basketball player who plays center for the NBA's Denver Nuggets. Jokić, renowned for his remarkable passing prowess and basketball acumen, has revolutionized the function of a contemporary NBA center. At 7 feet 2 inches (2.13 meters) tall, he has an array of skills that allow him to score, rebound, and create plays. Jokić became the second player in franchise history to win the NBA Most Valuable Player (MVP) title for the 2020–2021 season. The Nuggets' success in the league has been greatly attributed to his distinctive playing style and leadership on the floor. Jokić is well-known for his sportsmanship and humility off the court.

## Trae Young 🌟
![Trae GIF](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/a7c4f476-5b01-465b-9965-b55c3c3a4680)

American professional basketball player **Trae Young** was born on September 19, 1998, and he currently plays point guard for the Atlanta Hawks in the NBA. Young immediately established himself as one of the league's rising stars thanks to his remarkable ball-handling and scoring abilities. He has a great shooting range and excellent court vision, standing at 6 feet 1 inch (1.85 meters). Young's influence on the game was demonstrated in his selection as an NBA All-Star in 2020 and 2021. He is a key component of the Atlanta Hawks' future success because of his electric playing style and knack for making big shots.

## 💻 Codes used for the Face Recognition
_The following codes were used to program the face recognition task:_

### 🏀𝐈𝐦𝐩𝐨𝐫𝐭𝐢𝐧𝐠 𝐈𝐦𝐚𝐠𝐞𝐬 𝐟𝐫𝐨𝐦 𝐆𝐢𝐭𝐡𝐮𝐛 𝐚𝐧𝐝 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐢𝐧𝐠 𝐅𝐚𝐜𝐞_𝐑𝐞𝐜𝐨𝐠𝐧𝐢𝐭𝐢𝐨𝐧
</div>

    !git clone https://github.com/GTFider/Group6_Finals_FaceRecognition.git
    !pip install face_recognition
    %cd Group6_Finals_FaceRecognition

### 🏀𝐄𝐧𝐜𝐨𝐝𝐢𝐧𝐠 𝐏𝐫𝐨𝐟𝐢𝐥𝐞𝐬 𝐔𝐬𝐢𝐧𝐠 𝐊𝐧𝐨𝐰𝐧 𝐅𝐚𝐜𝐞 𝐈𝐦𝐚𝐠𝐞𝐬
</div>

    import face_recognition
    import numpy as np
    from google.colab.patches import cv2_imshow
    import cv2

    # Creating the encoding profiles
    face_1 = face_recognition.load_image_file("Nikola Jokic.jpg")
    face_1_encoding = face_recognition.face_encodings(face_1)[0]

    face_2 = face_recognition.load_image_file("Trae Young.jpg")
    face_2_encoding = face_recognition.face_encodings(face_2)[0]

    face_3 = face_recognition.load_image_file("Luka Doncic.jpg")
    face_3_encoding = face_recognition.face_encodings(face_3)[0]

    face_4 = face_recognition.load_image_file("Giannis Antetokounmpo.jpg")
    face_4_encoding = face_recognition.face_encodings(face_4)[0]

    face_5 = face_recognition.load_image_file("Stephen Curry.jpg")
    face_5_encoding = face_recognition.face_encodings(face_5)[0]

    known_face_encodings = [
                        face_1_encoding,
                        face_2_encoding,
                        face_3_encoding,
                        face_4_encoding,
                        face_5_encoding
]

    known_face_names = [
                     "Nikola Jokic",
                    "Trae Young",
                    "Luka Doncic",
                    "Giannis Antetokounmpo",
                    "Stephen Curry",
]

### 🏀𝐑𝐮𝐧𝐧𝐢𝐧𝐠 𝐨𝐟 𝐅𝐚𝐜𝐞 𝐑𝐞𝐜𝐨𝐠𝐧𝐢𝐭𝐢𝐨𝐧 𝐨𝐧 the NBA Players chosen:

Here is a Python method that uses OpenCV and the face_recognition module to recognize faces in an image. The code loads an unknown image, recognizes faces, and compares their encodings with a collection of known face endings. It then highlights the faces that are detected by drawing rectangles around them and labeling them with names. Finally, it shows the altered image, demonstrating the outcome of the face recognition process.

𝖥𝗈𝗋 𝗍𝗁𝖾 𝖿𝖺𝖼𝖾 𝗋𝖾𝖼𝗈𝗀𝗇𝗂𝗍𝗂𝗈𝗇 𝗈𝖿 𝗍𝗁𝖾 NBA Players chosen, 𝗍𝗁𝖾 𝗀𝗋𝗈𝗎𝗉 𝗎𝗍𝗂𝗅𝗂𝗓𝖾𝖽 𝗍𝗁𝗂𝗌 𝖼𝗈𝖽𝖾 𝖻𝗈𝗍𝗁 𝖿𝗈𝗋 𝐊𝐧𝐨𝐰𝐧 𝖺𝗇𝖽 𝐔𝐧𝐤𝐧𝐨𝐰𝐧 𝗂𝖽𝖾𝗇𝗍𝗂𝗍𝗂𝖾𝗌 𝗂𝗇𝗍𝖾𝗇𝖽𝖾𝖽 𝖿𝗈𝗋 𝗍𝗁𝗂𝗌 given 𝖺𝖼𝗍𝗂𝗏𝗂𝗍𝗒:

## _Known Images Face Recognition_

In Python, known image face recognition is the process of recognizing and authenticating people using previously collected facial data. This usually entails detecting and extracting facial features using facial recognition tools like OpenCV or dlib. Typically, the recognized facial features are kept as facial descriptors or embeddings, signifying distinct attributes of every face. To identify and match recognized faces, these embeddings are compared in real time with specific facial traits. Known face recognition is frequently used in access control, security systems, and other applications where person identification is essential.
>
>         
<div align="center">

&nbsp;

---

## Denver Nuggets Face Recognition

---

### _Nikola Jokić with some of his teammates in his Denver Nuggets Team_

</div>

![Denver Nuggets](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/d4429272-49f6-44b3-91bd-91839c803573)

### 💻 Code Used:
</div>

    file_name = "Denver Nuggets.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Atlanta Hawks Face Recognition

---

### _Trae Young with some of his teammates in his Atlanta Hawks Team_

</div>

![Atlanta Hawks](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/bf81b9c6-e818-4686-b5f7-ccfdd6a63243)

### 💻 Code Used:
</div>

    file_name = "Atlanta Hawks.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Dallas Mavericks Face Recognition

---

### _Luka Dončić with some of his teammates in his Dallas Mavericks Team_

</div>

![Dallas Mavericks](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/fccd540b-b3c9-4a95-9591-3a2e2448cc93)

### 💻 Code Used:
</div>

    file_name = "Dallas Mavericks.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Milwaukee Bucks Face Recognition

---

### _Giannis Antetokoumnpo with some of his teammates in his Milwaukee Bucks Team_

</div>

![Milwaukee Bucks](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/ad6c54cf-11b7-4719-8288-113359ceee71)

### 💻 Code Used:
</div>

    file_name = "Milwaukee Bucks.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Golden State Warriors Face Recognition

---

### _Stephen Curry with some of his teammates in his Golden State Warriors Team_

</div>

![Golden State Warriors](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/4725bd44-6270-4682-a248-ed7ff4c4c0b1)

### 💻 Code Used:
</div>

    file_name = "Golden State Warriors.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

## _Unknown Image Face Recognition_
Python facial recognition for unknown photos is the process of identifying faces in pictures where the subjects are not known beforehand or have not been entered into a database. To find and identify faces in photos, this approach frequently uses machine learning methods, such as deep learning-based models. After face detection using well-known libraries like OpenCV or dlib, a face recognition model—such as a deep neural network—is used to see if the face in the picture matches any known faces. For these models to generalize and identify faces that weren't specifically included in the training set, they must be trained on huge datasets. Applications for unknown picture face recognition include population analysis, surveillance, and photo tagging.

## Other Teams and Players Face Recognition
This section showcases images of teams with different players that were unknown to the Python program.

>
>         
<div align="center">

&nbsp;

---

## Team No. 1 Face Recognition

---

### _Los Angeles Lakers Team_

</div>

![Los Angeles Lakers](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/12237865-c7f9-42ad-b01f-89dd3e5a1fc4)

### 💻 Code Used:
</div>

    file_name = "Los Angeles Lakers.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, bottom-40), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Team No. 2 Face Recognition

---

### _New York Knicks Team_

</div>

![New York Knicks](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/ea933b27-e702-46f7-9f33-69c7c7e240f8)

### 💻 Code Used:
</div>

    file_name = "New York Knicks.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Team No. 3 Face Recognition

---

### _Charlotte Hornets Team_

</div>

![Charlotte Hornets](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/c765f41f-8bc4-4d8c-b90a-55124b65f1ca)

### 💻 Code Used:
</div>

    file_name = "Charlotte Hornets.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Team No. 4 Face Recognition

---

### _Minnesota Timberwolves Team_

</div>

![Minnesota Timberwolves](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/568da5d1-0bb6-44c7-8189-cc86893f4140)

### 💻 Code Used:
</div>

    file_name = "Minnesota Timberwolves.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Team No. 5 Face Recognition

---

### _Miami Heat Team_

</div>

![Miami Heat](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/c2224fd2-2265-4c94-a9fb-553685ed4c7b)

### 💻 Code Used:
</div>

    file_name = "Miami Heat.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Team No. 6 Face Recognition

---

### _San Antonio Spurs Team_

</div>

![San Antonio Spurs](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/84a32d87-29f3-4418-91a7-443c79d513e9)

### 💻 Code Used:
</div>

    file_name = "San Antonio Spurs.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Team No. 7 Face Recognition

---

### _Indiana Pacers Team_

</div>

![Indiana Pacers](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/fe2b4878-7513-41eb-a710-f4d6787a00e6)

### 💻 Code Used:
</div>

    file_name = "Indiana Pacers.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Team No. 8 Face Recognition

---

### _Houston Rockets Team_

</div>

![Houston Rockets](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/d953b11e-c12c-432d-974c-925ed2b11692)

### 💻 Code Used:
</div>

    file_name = "Houston Rockets.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Team No. 9 Face Recognition

---

### _Cleveland Cavaliers Team_

</div>

![Cleveland Cavaliers](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/4eebfd19-d971-4147-a27e-75384134e9f6)

### 💻 Code Used:
</div>

    file_name = "Cleveland Cavaliers.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

>
>         
<div align="center">

&nbsp;

---

## Team No. 10 Face Recognition

---

### _Chicago Bulls Team_

</div>

![Chicago Bulls](https://github.com/jujuvml/Group6_Finals_FaceRecognition/assets/143612018/7d5c3283-6cc9-4a8e-895a-ec86bcae7700)

### 💻 Code Used:
</div>

    file_name = "Chicago Bulls.jpg"
    unknown_image = face_recognition.load_image_file(file_name)
    unknown_image_to_draw = cv2.imread(file_name)

    face_locations = face_recognition.face_locations(unknown_image)
    face_encodings = face_recognition.face_encodings(unknown_image, face_locations)

    for (top,right, bottom, left), face_encoding in zip(face_locations, face_encodings):
      matches = face_recognition.compare_faces(known_face_encodings, face_encoding)

      name = "Unknown"

      face_distances = face_recognition.face_distance(known_face_encodings, face_encoding)
      best_match_index = np.argmin(face_distances)
      if matches[best_match_index]:
        name = known_face_names[best_match_index]
      cv2.rectangle(unknown_image_to_draw, (left, top), (right, bottom),(0,255,0),3)
      cv2.putText(unknown_image_to_draw,name, (left, top-20), cv2.FONT_HERSHEY_SIMPLEX,1,(0,0,255),2, cv2.LINE_AA)

    cv2_imshow(unknown_image_to_draw)

## 🔗 REFERENCES:
### _For NBA Players:_


- **Trae Young** - https://cdn.nba.com/headshots/nba/latest/1040x760/1629027.png

- **Stephen Curry** - https://cdn.nba.com/headshots/nba/latest/1040x760/201939.png

- **Giannis Antetokoumnpo** - https://cdn.nba.com/headshots/nba/latest/1040x760/203507.png

- **Nikola Jokić** - https://cdn.nba.com/headshots/nba/latest/1040x760/203999.png

- **Luka Dončić** - https://cdn.nba.com/headshots/nba/latest/1040x760/1629029.png


### _For NBA Teams:_


- **Atlanta Hawks** - https://ca-times.brightspotcdn.com/dims4/default/164d32c/2147483647/strip/false/crop/4224x2817+0+0/resize/1486x991!/quality/75/?url=https%3A%2F%2Fcalifornia-times-brightspot.s3.amazonaws.com%2F67%2F2a%2F709cef9e4ae1f083820e599cb842%2F6d896abe15844eecb9061769ea592bac

- **Golden State Warriors** - https://warriorswire.usatoday.com/wp-content/uploads/sites/33/2022/10/USATSI_19233965-e1666030305542.jpg?w=1000&h=600&crop=1

- **Milwaukee Bucks** - https://onmilwaukee.com/images/articles/bu/bucks-offseason-questions/bucks-offseason-questions_fullsize_story1.jpg

- **Denver Nuggets** - https://cdn.thednvr.com/wp-content/uploads/2023/11/09101526/USATSI_21852964-3000x2000.jpg

- **Dallas Mavericks** - https://fivethirtyeight.com/wp-content/uploads/2022/05/AP22131301741536-4x3-1.jpg?w=916

- **Los Angeles Lakers** - https://i.guim.co.uk/img/media/f289df4e3fe389e6d84aea24d0c2eaec8e0553e4/0_261_4968_2982/master/4968.jpg?width=465&dpr=1&s=none

- **New York Knicks** - https://images.ctfassets.net/1aemqu6a6t65/6FYwuUgvdzvWIX6loI4MZ7/28ce1fa7dadb1cf663a3280b77a81a68/new-york-knicks-msg-nyc_031821_2335?w=1200&h=800&q=75

- **Charlotte Hornets** - https://fantomsportsindustries.com/wp-content/uploads/2023/10/the-charlotte-hornets-picked-up-a-big-win-over-golden-state-with-a-strong-defensive-effort-in-the-fourth-quarter_9qdh948lg3ga14iph4ii1806k.jpg

- **Minnesota Timberwolves** - https://www.twincities.com/wp-content/uploads/2023/12/AP23329013510533.jpg?w=525

- **Miami Heat** - https://images.rr.sapo.pt/40825932237966121002defaultlarge_1024.jpg

- **San Antonio Spurs** - https://images2.minutemediacdn.com/image/upload/c_crop,w_4074,h_2291,x_0,y_54/c_fill,w_720,ar_16:9,f_auto,q_auto,g_auto/images/GettyImages/mmsport/29/01ha7tk06n5kf0313cn3.jpg

- **Indiana Pacers** - https://www.hispanosnba.com/imagenes/equipos/indiana-pacers-t2.jpg

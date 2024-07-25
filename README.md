Project submitted at Shecodes Hackathon 2021

## Introduction

COVID-19 has moved everything online: work, school, social interactions. For many people, this has caused a lot of inconvenience, but these difficulties are multiplied for those who are deaf and mute. Because daily communication for them inherently faces more barriers.

This project will build a new online meeting platform, allowing deaf-mute people to access and express their thoughts to anyone through hand sign language while normal people can hear and speak with deaf and mute people.

## Function

- Convert sign language to voice
- Convert voice to text
- Sign language recognition models has accuracy > 90% 

## Technology used

- Apply computer vision and deep learning to convert sign language to speech: opencv, tensorflow
- Processing audio into text: Google api
- Web development: flask, html, css, bootstrap

## Future development

- Collect more data about Vietnamese sign language
- Improve model accuracy
- Develop products that can meet real-time needs

## Difficulty

- Members are newbies in web programming
- Spends a lot of time collecting data and searching for testing models
- Online hackathons create many barriers to communication and teamwork

## Lesson learned

- Programming and web development
- Hackathon mindset from ideating, testing and developing an AI software
- Teamwork and time management skills

## Using

- Clone this repo to your computer and move it to the repo folder

- Install `ffmpeg` in the usage environment

Example: For anaconda

```
conda install ffmpeg -y
```

- Install libraries

```
pip install -r requirements.txt
```

- Download [model weights](https://drive.google.com/file/d/12Cgl9u-WAJZ6WitrPgH20t5J1ookzMSS/view?usp=sharing)

- Run the server

```
python app.py
```

- Server will run at http://127.0.0.1:5000/

## Demo
Watch the demo here: (https://drive.google.com/file/d/1Vx2xGbF1ksbAapOBQQ3oKGuJEzg4g86-/view?usp=sharing)


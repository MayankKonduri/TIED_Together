# Tied Together ♫

A web application connecting middle school band members with high school tutors
for free private instruction.

[Live site](https://tiedtogether.github.io) · [Demo video](http://bit.ly/tied-together-demo)

---

## Overview

Middle school band students who want extra help often can't afford paid private
lessons. Tied Together matches them with high school band members willing to
tutor for free. Students sign up by scanning a QR code and entering their
details; tutors sign in with their district ID and receive a ranked list of
students to choose from.

---

## Features

**Verified tutor accounts.** Tutors register with their Katy ISD student ID, so
only district students can claim a tutor account.

**Ranked student matching.** Each tutor sees a personalized, sorted list of
interested students, ordered by grade, skill level, instrument, and whether the
student is already enrolled in paid private lessons.

**Flexible pairing.** A tutor can work with several students at once and
disconnect at any time, which returns that student to the pool for another tutor
to select.

**QR code student sign-up.** Prospective students reach the app by scanning a
QR code and entering their information to be picked up for lessons.

**Secure storage.** All data is stored on MongoDB Atlas.

---

## Screenshots

### Tutor

**Home**

![Tied Together home page](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/6cee8f38-93f2-4e26-b49c-4672c26768ad)

**Dashboard**

![Tutor dashboard listing interested students](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/eef6bea7-f33b-46b0-bdbb-b11c25f02931)

<details>
<summary>Sign up, sign in, and connect flow</summary>

<br>

Sign up:

![Tutor sign-up form](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/fcab20f4-b908-46d8-b9b0-6b8de95df597)

![Tutor sign-up form, continued](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/d3822350-8617-462f-a216-f81f02c2770c)

Sign in:

![Tutor sign-in screen](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/d2fde70e-2d4e-4936-afe1-c1f65537d65f)

Dashboard, continued:

![Tutor dashboard, expanded student detail](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/7f5c2cb2-2a5c-462d-ad9f-87f6cda0bec2)

Connect:

![Tutor connecting with a selected student](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/3986376f-ca64-441a-8825-f1ede565be14)

![Confirmation after connecting with a student](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/196164a2-3448-406e-b228-b4b8fe39ae04)

</details>

### Student

**Sign up**

![Student sign-up form](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/be577e02-8df9-42f3-9c8f-fa2cfb1de59f)

<details>
<summary>Remaining sign-up steps</summary>

<br>

![Student sign-up form, instrument and skill level](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/cc3dcba5-8593-43b8-ab20-15600043af2f)

![Student sign-up confirmation](https://github.com/tiedtogether/tiedtogether.github.io/assets/105828651/4acdedfc-5ce1-44d0-b8f7-565b64971ba7)

</details>

---

## Tech Stack

<!-- TODO: fill in — this is the first thing most visitors look for. -->

| Layer | Technology |
|:---|:---|
| Frontend | React |
| Backend | Java |
| Database | MongoDB Atlas |
| Hosting | GitHub Pages |

---

## Running Locally

<!-- TODO: replace with the real commands. -->

```bash
git clone https://github.com/tiedtogether/tiedtogether.github.io.git
cd tiedtogether.github.io
```

A MongoDB Atlas connection string is required. Add it to a `.env` file in the
project root:

```
MONGODB_URI=your-connection-string
```

---

## Team

Eric Li · Pranav Ullas · Mayank Konduri

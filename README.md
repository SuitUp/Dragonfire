# Dragonfire

Dragonfire is an open source virtual assistant project for Ubuntu based Linux distributions

![Dragonfire](https://raw.githubusercontent.com/mertyildiran/Dragonfire/master/docs/img/dragonfire.gif)

<p align="center"><i>Dragonfire will never leave your questions unanswered.</i></p>

<p align="center"><b>Dragonfire is not The Next Big Thing but a spectacular combination of freely available technologies.</b></p>

<br>

Dragonfire does following tasks for each separate command, respectively:

 - Search across the built-in commands of Dragonfire
 - Try [AIML](http://teach.dragon.computer/gui/jquery/multibot_gui_with_chatlog.php)
 - Ask to [YodaQA](https://github.com/brmson/yodaqa)

<br>

### Version

0.9.2

### Installation

```Shell
wget https://raw.githubusercontent.com/mertyildiran/Dragonfire/master/install.sh && chmod +x install.sh && sudo ./install.sh
sudo pip install dragonfire
```

### Usage

```Shell
dragonfire
```

To activate Dragonfire say *DRAGONFIRE* or *HEY* or *WAKE UP*.

To deactivate her say *GO TO SLEEP*.

To silence her say *ENOUGH* or *SHUT UP*.

To kill her say *GOODBYE* or *BYE BYE* or *SEE YOU LATER*.

<br>

#### Built-in Commands

[Dragonfire DEVLOG #3 - Built-in Commands](https://youtu.be/krHUzY2DylI)

```
DRAGONFIRE | WAKE UP | HEY
GO TO SLEEP
ENOUGH | SHUT UP
WHO AM I | SAY MY NAME
MY TITLE IS LADY | I'M A LADY | I'M A WOMAN | I'M A GIRL
MY TITLE IS SIR | I'M A MAN | I'M A BOY
WHAT IS YOUR NAME
WHAT IS YOUR GENDER
FILE MANAGER | OPEN FILES
WEB BROWSER
OPEN BLENDER
PHOTOSHOP | PHOTO EDITOR
INKSCAPE | VECTOR GRAPHICS
VIDEO EDITOR
OPEN CAMERA
OPEN CALENDAR
OPEN CALCULATOR
OPEN STEAM
SOFTWARE CENTER
OFFICE SUITE
OPEN WRITER
OPEN MATH
OPEN IMPRESS
OPEN DRAW
KEYBOARD *
ENTER | NEW TAB | SWITCH TAB | CLOSE | GO BACK | GO FORWARD
SCROLL LEFT | SCROLL RIGHT | SCROLL UP | SCROLL DOWN
PLAY | PAUSE | SPACEBAR
SHUT DOWN THE COMPUTER
GOODBYE | BYE BYE | SEE YOU LATER
(SEARCH|FIND) * (IN|ON|AT|USING) WIKIPEDA
(SEARCH|FIND) * (IN|ON|AT|USING) YOUTUBE
```

<br>

#### AIML examples

[Dragonfire DEVLOG #4 - AIML](https://youtu.be/ujmRtqf2nxQ)

```
_______________________________________________________________

You: THE SUN IS HOT
Dragonfire: OK, I GET IT. THE SUN IS HOT
_______________________________________________________________

You: THE SUN IS YELLOW
Dragonfire: OK, I GET IT. THE SUN IS YELLOW
_______________________________________________________________

You: DESCRIBE THE SUN
Dragonfire: THE SUN IS HOT AND YELLOW
_______________________________________________________________

You: MY AGE IS 25
Dragonfire: OK, I GET IT. YOUR AGE IS 25
_______________________________________________________________

You: WHAT IS MY AGE
Dragonfire: YOUR AGE IS 25
_______________________________________________________________

You: MY PLACE OF BIRTH IS TURKEY
Dragonfire: OK, I GET IT. YOUR PLACE OF BIRTH IS TURKEY
_______________________________________________________________

You: WHERE IS MY PLACE OF BIRTH
Dragonfire: YOUR PLACE OF BIRTH IS TURKEY
_______________________________________________________________

You: YOU ARE JUST A COMPUTER PROGRAM
Dragonfire: OK, I GET IT. I'M JUST A COMPUTER PROGRAM
_______________________________________________________________

You: WHAT ARE YOU
Dragonfire: I'M JUST A COMPUTER PROGRAM
_______________________________________________________________

You: THE ATOMIC NUMBER OF GOLD IS 79
Dragonfire: OK, I GET IT. THE ATOMIC NUMBER OF GOLD IS 79
_______________________________________________________________

You: WHAT IS THE ATOMIC NUMBER OF GOLD
Dragonfire: THE ATOMIC NUMBER OF GOLD IS 79
_______________________________________________________________

```

<br>

#### YodaQA examples

[Dragonfire DEVLOG #5 - YodaQA ](https://youtu.be/FafUcxC0puM)

```
_______________________________________________________________

You: WHERE IS THE TIMES SQUARE
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|█████                                                       |

Dragonfire: NEW YORK CITY
_______________________________________________________________

You: WHAT IS THE HEIGHT OF BURJ KHALIFA
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|███████                                                     |

Dragonfire: 829.8
_______________________________________________________________

You: WHERE IS BURJ KHALIFA
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|███████                                                     |

Dragonfire: DUBAI
_______________________________________________________________

You: WHAT IS THE HEIGHT OF GREAT PYRAMID OF GIZA
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|███████                                                     |

Dragonfire: 138.8
_______________________________________________________________

You: WHO IS PLAYING JON SNOW IN GAME OF THRONES
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|███████████                                                 |

Dragonfire: KIT HARINGTON
_______________________________________________________________

You: WHAT IS THE ATOMIC NUMBER OF OXYGEN
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|███████                                                     |

Dragonfire: 8
_______________________________________________________________

You: WHAT IS THE POPULATION OF CHINA
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|████                                                        |

Dragonfire: ALMOST A QUARTER OF WORLD POPULATION
_______________________________________________________________

You: WHAT IS THE OFFICIAL LANGUAGE OF JAPAN
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|█████████                                                   |

Dragonfire: JAPANESE LANGUAGE
_______________________________________________________________

You: WHAT IS THE REAL NAME OF IRON MAN
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|███████████████                                             |

Dragonfire: TONY STARK
_______________________________________________________________

You: WHO IS THE CONQUEROR OF CONSTANTINOPLE
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|████████                                                    |

Dragonfire: MEHMED THE CONQUEROR
_______________________________________________________________

You: WHEN CONSTANTINOPLE WAS CONQUERED
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|███████                                                     |

Dragonfire: 1453
_______________________________________________________________

You: WHAT IS THE CAPITAL OF TURKEY
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|██████                                                      |

Dragonfire: ANKARA
_______________________________________________________________

You: WHAT IS THE LARGEST CITY OF TURKEY
Dragonfire: I NEED TO DO A BRIEF RESEARCH ON THE INTERNET. IT MAY TAKE UP TO 3 MINUTES, SO PLEASE BE PATIENT.
_______________________________________________________________

|███████████                                                 |

Dragonfire: ISTANBUL
_______________________________________________________________

```

<br>

#### Supported Distributions

 - KDE neon
 - elementary OS
 - Ubuntu

All modern releases (Ubuntu 12.04 LTS and above) of these distributions are fully supported. Any other Ubuntu based distributions are partially supported.

#### For generating .dict and .dfa files from .grammer and .voca files(for developers only), use:

```Shell
cd Dragonfire/dragonfire/
mkdfa sample
```

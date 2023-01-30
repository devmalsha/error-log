# 2023.01.30

## Error :01

![ERROR 01](20230130-E1.jpg)

## Error :02

not applying background color which set to body.
![ERROR 02](20230130-E2.jpg)

| ERROR                                            | SOLUTION                                                                                                                                                                                                                                                                                          |
| ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Stylesheet not loaded because of MIME type       | I was typed "css/boostrap.min.css" . But it should be "css/bootstrap.min/css"for more detail : https://developerf1.com/how-to/solving-stylesheet-not-loaded-because-of-mime-type#:~:text=Refused%20to%20apply%20style%20from,this%20is%20not%20a%20node.                                          |
| not applying background color which set to body. | Solution 01: Set the link which call bootsrap.min.css before the link which call style.css file.\ Solution 02: Create a class including background-color attribute and call it inside the `<body>` tag on html file. This will override the default css rules which applied by bootstrap.min.css. |

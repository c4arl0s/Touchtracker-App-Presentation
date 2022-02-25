# [go back to overview](https://github.com/c4arl0s#ios-apps-using-swiftuikit)

# [Beginning of Touchtracker App](https://github.com/c4arl0s/18TouchEventsAndUIResponder#18-touch-events-and-uiresponder---content)

An app that lets the user draw by touching the screen

| Notes                                                                                                                         | Code                                                                                                                          | Diagrams                                                                                                                      | xcodeproj                                                                                                                     |
|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://user-images.githubusercontent.com/24994818/124359838-4c12d700-dbec-11eb-9186-2f50b586230c.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124359793-1a9a0b80-dbec-11eb-951d-54d87dfef74d.png" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124359917-9431f980-dbec-11eb-81c9-2d30f6857158.jpg" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/124359956-bdeb2080-dbec-11eb-8a08-5ece008c8e0e.gif" width="250"> |

1. [x] [1. Touch Events](https://github.com/c4arl0s/18TouchEventsAndUIResponder#1-touch-events)
    - [x] [Life Cycle of a Touch](https://github.com/c4arl0s/18TouchEventsAndUIResponder#life-cycle-of-a-touch)
    - [x] [Conclusion about how touch objects work:](https://github.com/c4arl0s/18TouchEventsAndUIResponder#conclusion-about-how-touch-objects-work)
    - [x] [What about multiple touches](https://github.com/c4arl0s/18TouchEventsAndUIResponder#what-about-multiple-touches-)
2. [x] [2. Creating the TouchTracker Application](https://github.com/c4arl0s/18TouchEventsAndUIResponder#2-creating-the-touchtracker-application)
3. [x] [3. Creating the Line Struct](https://github.com/c4arl0s/18TouchEventsAndUIResponder#3-creating-the-line-struct)
4. [x] [4. Value types vs reference types](https://github.com/c4arl0s/18TouchEventsAndUIResponder#4-value-types-vs-reference-types)
5. [x] [5. Creating DrawView](https://github.com/c4arl0s/18TouchEventsAndUIResponder#5-creating-drawview)
6. [x] [6. Drawing with DrawView](https://github.com/c4arl0s/18TouchEventsAndUIResponder#6-drawing-with-drawview)
7. [x] [7. Turning Touches into Lines](https://github.com/c4arl0s/18TouchEventsAndUIResponder#7-turning-touches-into-lines)
    - [x] [Create the Line:](https://github.com/c4arl0s/18TouchEventsAndUIResponder#create-the-line)
    - [x] [When touchesBegan](https://github.com/c4arl0s/18TouchEventsAndUIResponder#when-touchesbegan)
    - [x] [When touchesMoved](https://github.com/c4arl0s/18TouchEventsAndUIResponder#when-touchesmoved)
    - [x] [When touchesEnded](https://github.com/c4arl0s/18TouchEventsAndUIResponder#when-touchesended)
8. [x] [8. Handling multiple touches](https://github.com/c4arl0s/18TouchEventsAndUIResponder#8-handling-multiple-touches)
9. [x] [9. @IBInspectable](https://github.com/c4arl0s/18TouchEventsAndUIResponder#9-ibinspectable)
10. [x] [10. For more curious: The responder chain](https://github.com/c4arl0s/18TouchEventsAndUIResponder#10-for-more-curious-the-responder-chain)
11. [x] [11. For the More Curious: UIControl](https://github.com/c4arl0s/18TouchEventsAndUIResponder#11-for-the-more-curious-uicontrol)

# [19. UIGesture Recognizer And UIMenuController](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#19-uigesture-recognizer-and-uimenucontroller)

| At a glance: Notes                                                                                                           |                                                                                                                              |                                                                                                                              |                                                                                                                              |
|------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://user-images.githubusercontent.com/24994818/79251698-1c8c7900-7e46-11ea-8c23-d914a6a01db1.PNG" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/79261331-48fbc180-7e55-11ea-9e5c-12d90c09bac5.gif" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/91628015-55eefc80-e981-11ea-91e5-2891a1475378.gif" width="250"> | <img src="https://user-images.githubusercontent.com/24994818/91629046-f564bd00-e98a-11ea-9cfe-24fd1b7addf7.gif" width="250"> |

0. [x] [0. UIGestureRecognizer and UIMenuController - Intro](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#19-uigesture-recognizer-and-uimenucontroller)
1. [x] [1. UIGestureRecognizer Subclasses](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#1-uigesturerecognizer-subclasses)
2. [x] [2. Detecting Taps with UITapGestureRecognizer](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#2-detecting-taps-with-uitapgesturerecognizer)
3. [x] [3. Multiple Gesture Recognizer](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#3-multiple-gesture-recognizer)
4. [x] [4. UIMenuController](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#4-uimenucontroller)
5. [x] [5. More Gesture Recognizers](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#5-more-gesture-recognizers)
6. [x] [6. UILongPressGestureRecognizer](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#6-uilongpressgesturerecognizer)
   - [x] [Checking Recognizer State property](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#checking-recognizer-state-property)
7. [x] [7. UIPanGestureRecognizer and simultaneous recognizers](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#7-uipangesturerecognizer-and-simultaneous-recognizers)
   - [x] [What is cancelsTouchesInView ?](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#what-is-cancelstouchesinview-)
   - [x] [GestureRecognizer should Recognize Simultaneously With OtherGestureRecognizer ?](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#gesturerecognizer-should-recognize-simultaneously-with-othergesturerecognizer-)
   - [x] [Enable panning while long pressing](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#enable-panning-while-long-pressing)
   - [x] [Pan gesture recognizer supports the change state](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#pan-gesture-recognizer-supports-the-change-state)
8. [x] [8. More on UIGestureRecognizer](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#8-more-on-uigesturerecognizer)
9. [x] [9. Silver Challenge: Mysterious Lines](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#9-silver-challenge-mysterious-lines)
10. [x] [10. Gold Challenge: Speed and Size](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#10-gold-challenge-speed-and-size)
11. [x] [11. Platinum Challenge: Colors](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#11-platinum-challenge-colors)
12. [x] [12. For the More Curious: UIMenuController and UIResponderStandarEditActions](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#12-for-the-more-curious-uimenucontroller-and-uiresponderstandareditactions)

### [End of Touchtracker App](https://github.com/c4arl0s/19UIGestureRecognizerAndUIMenuController#9-silver-challenge-mysterious-lines)

### Follow this simple code to generate a calendar file (Google,Outlook,iCloud Calendar etc) for your personal NITRIS schedule!

The current stage of this project uses a Jupyter Notebook file which should run on any preferred IDE and an updated version of python with the ipykernel.

### Steps to Run:

1. Copy the whole text of registered courses for the first input.
   ![Copy the Whole Text of Registered Courses](courses.png)

    Should look almost like this:
    \# Subject Section Time Slot Faculty Name Backlog TC AB LE TA
    1 EE4101 : Power System Protection S1 TA Dr. Shekha Rai 0 0 0 0
    2 EE4103 : High Voltage Engineering and HVDC Transmission S1 ZA Prof. Subrata Karmakar 0 0 0 0
    3 EE4405 : Digital Communication S1 TB Dr. Suman Kr. Dey 0 0 0 0
    4 SM6611 : Business Research Methodology S2 TF Dr. Kunja Sambashiva Rao 0 0 0 0
    5 EE4903 : Seminar and Technical Writing - I S1 XX Prof. Asim Kumar Naskar X X X X
    6 EE4091 : Research Project - I S1 XX Prof. Ananyo Sengupta X X X X
    7 EE4701 : Power Systems Laboratory S2 PY Dr. Shekha Rai 0 0 0 0
    8 EE4703 : Communication Systems Laboratory S2 PX Dr. Suman Kr. Dey 0 0 0 0
    9 EE4705 : Control and Electrical System Design S2 XX Dr. Arijit Guha 0 0 0 0

2. Copy the whole text of timetable for the second input.
   ![Copy the Whole Text of TimeTable](timetable.png)

    Should look almost like this:
    PERIOD
    DAY 08.00 hr
    08.55 hr 09.00 hr
    09.55 hr 10.00 hr
    10.55 hr 11.05 hr
    12.00 hr 12.00 hr
    13.15 hr 13.15 hr
    14.10 hr 14.15 hr
    15.10 hr 15.15 hr
    16.10 hr 16.20 hr
    17.15 hr 17.20 hr
    18.15 hr
    MONDAY EE4101 EE4405 - - L
    U
    N
    C
    H - - - SM6611 EE4103
    TUESDAY EE4405 - - - - - - SM6611 -
    WEDNESDAY - EE4703 EE4703 EE4703 - EE4701 EE4701 EE4701 EE4103
    THURSDAY - - EE4101 - - - - SM6611 -
    FRIDAY - EE4101 EE4405 - - - - - EE4103

3. Run the remaining code, a file 'ClassSchedule.ics' will be created.

4. Simply import the file to any of your Calendar App.

### Connect with me:

[<img align="left" alt="codeSTACKr.com" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][website]
[<img align="left" alt="codeSTACKr | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]
[<img align="left" alt="codeSTACKr | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="codeSTACKr | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter]

[website]: https://swagatkumar.net/
[twitter]: https://twitter.com/SwagatK24497938
[youtube]: https://youtube.com/codeSTACKr
[instagram]: https://www.instagram.com/swagatkumarflute/
[linkedin]: https://www.linkedin.com/in/swagat-kumar/

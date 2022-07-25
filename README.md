These test automation scripts are written for the Basiq.io purpose. The scripts are written using Selenium 3 and python.
Before running any of these tests on your local device you need to download the latest Chrome Web Driver file from https://chromedriver.chromium.org/downloads . Make sure that your Google Chrome browser version is the same as Chrome Web Driver version.
Also (for Mac users) if you have issue to run the tests beacuse of the error message "Chromedriver cannot be opened because the developer cannot be verified. Unable to launch the chrome browser", please do following:
1) Open terminal
2) Navigate to path where your chromedriver file is located
3) Execute command: xattr -d com.apple.quarantine (location of your web driver, ex. /usr/local/bin/chromedriver)
4) Try to run the test again

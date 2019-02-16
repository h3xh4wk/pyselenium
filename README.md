Python Bindings for Selenium
====================================

Setup
---------
Install Python in your OS and Clone/Download this repository on your local drive.

Ensure that apprpriate driver such as chromedriver and geckodriver are in
user's `PATH`. 

You can download the drivers from the below mentioned links:-

1. Chrome Driver[http://chromedriver.chromium.org/downloads]
2. Geckco Driver[https://github.com/mozilla/geckodriver/releases]

The drivers can be kept at the root path of this project.

Install `pytest` using the below command

```bash
pip install pytest
```

Examples of running unit tests
---------------------------------

Here are examples of running the unit tests

```bash

# One test using Chrome
py.test.exe
test/selenium/webdriver/common/window_switching_tests.py::testShouldThrowNoSuchWindowExceptionOnAnyElementOperationIfAWindowIsClosed
--driver=Chrome

# using Marionette for a suite
py.test.exe test/selenium/webdriver/common/ --driver=Marionette

```


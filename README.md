# XPATH-AUTOMATION-TESTING-08-10-2026-

```
from selenium import webdriver
from selenium.webdriver.common.by import By
from selenium.webdriver.support.ui import WebDriverWait
from selenium.webdriver.support import expected_conditions as EC
import time

driver = webdriver.Chrome()
driver.get("https://demo.automationtesting.in/Register.html?utm_source=chatgpt.com")
time.sleep(5)

driver.find_element(By.XPATH,"//*[@placeholder='First Name']").send_keys("shahith")
driver.find_element(By.XPATH,"//*[@placeholder='Last Name')]").send_keys("s")
time.sleep(5)
driver.find_element(By.XPATH,"//*[contains(@id,'firstpassword')]").send_keys("shahith2005")
driver.find_element(By.XPATH,"//*[@type='email' or  @ng-model='EmailAdress']").send_keys("shahshah07@gmail.com")
driver.find_element(By.XPATH,"//*[starts-with(@ng-model,'Ph')]").send_keys("7623175494")
driver.find_element(By.XPATH,"//*[@value='Male' and @type='radio']").click()
time.sleep(5)
driver.find_element(By.XPATH,"//*[@value='Cricket']/parent::div/child::input").click()
time.sleep(5)
driver.find_element(By.XPATH,"//*[@value='Movies']/ancestor::div[1]/child::input").click()
time.sleep(5)
driver.find_element(By.XPATH,"//*[@class='form-group'][6]/child::div/div[3]/input").click()
time.sleep(5)
dropdown= driver.find_element(By.XPATH,"//Select*[@id='msdd']")
dropdown.select_by_visible_text("Tamil")
time.sleep(5)
driver.find_element(By.XPATH,"//*[text()=' Submit ']").click()
time.sleep(5)



```


## GITHUB LINK:

https://github.com/Shahith18/XPATH-AUTOMATION-TESTING-08-10-2026-.git

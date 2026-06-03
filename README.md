# selenium-java-practice
project
WebDriver driver = new ChromeDriver();
driver.manage().window().Maximize();
driver.manage().Timeouts().implicitlywait(duration.ofseconds(10));
webdriverwait wait = new webdriverwait(driver,durationofseconds(10));
driver.get("URL");
wait.util(ExpectedCondition.visibilityofelementlocated(By.id("Login Page"));
driver.findelement(By.id("user name")).sendkeys("MAx");
driver.findelement(By.id("Password")).sendkeys("1234566");
driver.findelement(By.id("Login")).click();
webelement searchbox = wait.util(ExpectedCondition.Visibilityofelementlocated(By.id("searchbtw"));
searchbox.sendkeys("keys");
driver.findelement(By.id("search").click();
Webelement Add to cart = wait.util(ExpetedCondition.visibilityofelementlocated(By.id("Add to cart")).click();
driver.findelement(By.id("Go to cart")).click();
webelement proceedtopay =wait.util(expectedcondition.visibilityofelementlocated(By.id("payment").click();
driver.findelement(By.id("card Num")).sendkeys("223355668899");
driver.findelement(By.id("name")).sendkeys("symbol");
driver.findelement(By.id("cvv")).sendkeys("236");
Webelement countrydropdown = wait.util(expectedcondition.elementtobeclickble(By.id("Country")).click();
select s = new select(countrydropdown);
s.selectbyvisibletext("India");
Webelement Femaleradiobutton = wait.util(expectedcondition.visibilityofelementlocated(By.id("female"));
if(!femaleradiobutton.isselected()){
femaleradiobutton.select();
wait.util(expectedcondition.elementtobeclickable(By.id("place order")).click();
webelement successmessage = wait.util(expectedcondition.visibilityofelementlocated(By.id("success message")).gettext();
for(actualmessage.euqals().successmessage());
if(!actualmessage = successmessage){
System.out.println("Order placed");
}
else{
System.out.println("order failed");
}
catch(Exception e);
wait.util(Expectedcondition.visibilityofelementlocated(By.id("text")).getmessage();
for(e.errormessage)

takescreenshot = driver.("success message);

Takescreenshot ts = driver.(takescreenshot);
ts.src = file.getoutputas(OUTPUT.FILE());
ts.des = file(Path);
ts.file(Src,des);
driver.quit();





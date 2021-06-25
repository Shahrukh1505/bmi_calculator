# BMI Calculator
The Body Mass Index (BMI) or Quetelet index is a value derived from the mass weight and height of an individual. The BMI is defined as the body mass divided by the square of the body height, and is universally expressed in units of kg/m². By analyzing the BMI value, we can determine a diagnostic.

First step for the application is to define a layout letting users to enter weight and height values to calculate the BMI index. Besides, we will need a button to launch the BMI calculation and also a TextView to display the result.

When a user click on the calculate BMI button, the calculateBMI method is called. We get the values entered by the user for the weight and the height. The height is entered in centimeter. For the formula, we need to have a height in meter. So, we divide the value entered by 100. Then, we apply the formula to calculate the BMI :
# float bmi = weightValue / (heightValue * heightValue);
With the BMI value, we can display the result on the user interface. We define the displayBMI method for that. To determine the diagnostic associated to the BMI value, we are going to use the following table :
![1_CBc2ZhNwo3sppRlAe_of_Q](https://user-images.githubusercontent.com/62403839/123448555-a9a99100-d5f8-11eb-821d-1e0356196e0c.png)

The last step is just to display the BMI value and the diagnostic in the result TextView. After that, you can try the application and enjoy the BMI Calculator in action :
![Screenshot_20210625-205629](https://user-images.githubusercontent.com/62403839/123448620-b8904380-d5f8-11eb-8fcf-78bc0eba5817.png)

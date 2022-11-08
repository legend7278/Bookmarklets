javascript: var versionCalc = prompt('1). Basic Calculator\n2). Equations');

switch (versionCalc) {

  case '1':

    var operatorType = parseInt(prompt('1). Addition\n2). Subtraction\n3). Multiplication\n4). Division'));

    switch (operatorType) {
      case 1:
        var num1 = parseInt(prompt('First Number:'));
        var num2 = parseInt(prompt('Second Number:'));
        result = num1 + num2;
        break; 
      case 2:
        var num1 = parseInt(prompt('First Number:'));
        var num2 = parseInt(prompt('Second Number:'));
        result = num1 - num2;
        break; 
      case 3:
        var num1 = parseInt(prompt('First Number:'));
        var num2 = parseInt(prompt('Second Number:'));
        result = num1 * num2;
        break; 
      case 4:
        var num1 = parseInt(prompt('First Number:'));
        var num2 = parseInt(prompt('Second Number:'));
        result = num1 / num2;
        break; 
      default:
        alert('That is not a valid input. Input the number of the operation you are trying to run');
        break;
    };
  break;
  case '2':

    var equationType = parseInt(prompt('1). Slope\n2). Area of a circle\n3). Area of a square/rectangle\n4). Area of a triangle\n5). Volume of a cube\n6). Distance\n7). Time\n8). Speed'));

    switch (equationType) {

      case 1:
        m = parseInt(prompt("What is the rise/run? (M)"));
        x = parseInt(prompt("What is the distance of the line from the x-axis? (X)"));
        b = parseInt(prompt("What is the Y-Intercept? (B)"));
        result = (m * x) + b;
        break;
      case 2:
        r = parseInt(prompt('What is the radius of the circle? (R)'));
        r2 = r * r;
        result = r2 * 3.14;
        break;
      case 3:
        l = parseInt(prompt('What is the length?'));
        w = parseInt(prompt('What is the width?'));
        result = l * w;
        break;
      case 4:
        b = parseInt(prompt("What is the base of the triangle?"));
        h = parseInt(prompt("what is the height of the triangle?"));
        result = (b * h) / 2;
        break;
      case 5:
        l = parseInt(prompt('What is the length?'));
        w = parseInt(prompt('What is the width?'));
        h = parseInt(prompt('What is the height?'));
        result = l * w * h;
        break; 
      case 6:
        s = parseInt(prompt('What is the speed?'));
        t = parseInt(prompt('What is the time?'));
        result = s * t;
        break;
      case 7:
        s = parseInt(prompt('What is the speed?'));
        d = parseInt(prompt('What is the distance?'));
        result = d / s;
        break;
      case 8:
        s = parseInt(prompt('What is the time?'));
        d = parseInt(prompt('What is the distance?'));
        result = d / t;
        break;
      
      default:
        alert('That is not a valid input. Input the number of the operation you are trying to run');
        break;
    };
  break;
  default:
    alert('That is not a valid input. Input the number of the operation you are trying to run');  
};
alert('Your answer is ' + result);

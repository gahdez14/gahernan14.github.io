---
layout: essay
type: essay
title: "Is JavaScript as Bad as They Say??! First Impressions from an ICS314 Student"
# All dates must be YYYY-MM-DD format!
date: 2023-08-30
published: false
labels:
  - Engineering
---

# Previous Experience Comparison
With previous experience in Java, C++ and Python, my expectation of Javascript was that it would be outdated, slow or inefficient.  I remember having seen so many programs in the early days of internet running off of Javascript, and naturally assumed that we’ve come a way since then.  However, it was clear to see a difference in the efficacy of the code in looking at a single prompt.  

# C++ and Javascript Comparison 
The following is a prompt for a temperature conversion function:
If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. Find the sum of all the multiples of 3 or 5 below 1000.

## A C++ solution looks like this:

	#include <iostream>
	#include <string>

    double TemperatureConverter(int temperature, const std::string& temperatureType) {
        if (temperatureType == "F") {
         return (temperature - 32) * 5.0/9.0;
        } else if (temperatureType == "C") {
        	return (temperature * 9.0/5.0) + 32;
    	} else {
         std::cout << "Illegal temperature type" << std::endl;
    exit(EXIT_FAILURE);  // Exiting the program due to invalid input    
     }
     }

    int main() {
       // Test cases
        std::cout << TemperatureConverter(32, "F") << std::endl;    //Should print 0 (Celsius)
       std::cout << TemperatureConverter(0, "C") << std::endl;     // Should print 32 (Fahrenheit)
     std::cout << TemperatureConverter(100, "K") << std::endl;   // Should print "Illegal temperature type" and exit

       		return 0;
	    }

## A Solution in Javascript Could be Quicker:

    function projectEulerOne (maxNum) {
	    var total = 0;
 	    for (let i = 0; i <maxNum; i++) {
        if ((( i % 3) == 0) || (( i % 5) == 0 )) {
         total += i;
         }
         }
         return total;
         }
         console.log(projectEulerOne(1000));

# New Functions
Learning the utility of ES6 did take time, and will likely continue to take time.  Initially, the use of arrow functions seemed alien enough, but became intuitive after some repetition.  There are functions that are immediately useful and welcome.  For example, the ability to Destructure arrays and properties from objects can immediately shrink down a task that previously would require a precise homemade function to accomplish. In general, the WOD methodology of learning definitely forces the repetition and, although stressful, has been useful in instilling the idea of "coding with a purpose."

# Known Knowns and Known Unknowns
Although there are many “known” useful functions, there are functionalities whose utility is still unknown to me.  For example, the use of promises seems like a useful tool, but how it will be useful has yet to be seen.  Importing and exporting modules is another example.  Overall, the simplicity of Javascript easily makes it more friendly, useful, and pithy than other languages.  

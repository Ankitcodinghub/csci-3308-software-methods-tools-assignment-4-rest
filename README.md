# csci-3308-software-methods-tools-assignment-4-rest
**TO GET THIS SOLUTION VISIT:** [CSCI 3308 Software Methods & Tools Assignment #4 REST](https://www.ankitcodinghub.com/product/csci-3308-software-methods-tools-assignment-4-rest/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;9741&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI 3308 Software Methods \u0026amp; Tools  Assignment #4 REST&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<div class="product-description">Objectives

• Access information via REST

• Work with JSON formatted data

• Display data with SVG file and JQuery

• Use Google to find answers

• Recommend you work in pairs (If you do so, only ONE person submits in Moodle)

Assignment

In this assignment create a web page showing the weather across the USA.Requirements/Specifications/Steps

Note: you will need an API key (as done in lab). To do so, go to:

<a href="http://openweathermap.org/appid" target="_blank" rel="nofollow noopener">http://openweathermap.org/appid</a>&nbsp;And click on Sign up. Fill in to create a new account. On success, you will see your API key. Copy it, and then click on the link at the bottom “How to work with your API key”. Notice how the call needs to be set up, and add the id and API key to your string when you call urlopen.

1. First step is that you need a map of the USA. We will use the SVG file format from Wikipedia:

a. Info:&nbsp;<a href="https://en.wikipedia.org/wiki/File:Blank_US_Map.svg" target="_blank" rel="nofollow noopener">http://en.wikipedia.org/wiki/File:Blank_US_Map.svg</a>

b. File to download:

<a href="https://upload.wikimedia.org/wikipedia/commons/3/32/Blank_US_Map.svg" target="_blank" rel="nofollow noopener">http://upload.wikimedia.org/wikipedia/commons/3/32/Blank_US_Map.svg</a>

2. Now create a new HTML file named Firstname_Lastname_HW4.html

3. In your HTML file, add the following code to create a web page:

&lt;html

&lt;head

&lt;titleHW # Your last name(s)&lt;/title

&lt;/head

&lt;body

4. On the next line in the file, insert the US map you downloaded. Copy-paste isn’t very effective here, but you can do this in vim with the following:

:r Blank_US_Map.svg

5. Run a python server on your machine (Use the CGI version).

6. Test in your browser – the map of the US should show up.

7. Now convert this to a python CGI script that prints this HTML code.

a. Copy your html file to a new file named&nbsp;<a href="http://firstname_lastname_hw4.py/" target="_blank" rel="nofollow noopener">Firstname_Lastname_HW4.py</a>

b. Be sure to put this in the cgi-bin directory like we did in lectures.

Check permissions!

c. The first line in this file should be the shebang stuff.

d. Then add this:

print “Content-type: text/html”

print

You DO need the extra print!e. Then convert the code we have already to be in a string.

The secret to doing this is to use the multi-line quotes, such as:

contents = ‘’’

&lt;html

&lt;body

… etc.

‘’’

print contents

You should now see the map again, via the python script.

8. Now we want to call the URL we used in lab to get the weather. To start, do this with Boulder, CO.

To do this in python, if you Google how to read the JSON from a URL you can find a great answer at:

<a href="http://stackoverflow.com/questions/13921910/python-urllib2-receive-json-response-from-url" target="_blank" rel="nofollow noopener">http://stackoverflow.com/questions/13921910/python-urllib2-receive-json-response-from-url</a>

Remember, if you use this source then attribute it in your code!

a. If you print out the results, you may notice the letter ‘u’ everywhere.

This means it is returning the values in Unicode.

Search Google for a solution to convert to strings. Be sure to attribute your

source!

At this point you should now see something like this:

9. Our next step is to test manually changing the colors of the states. Add the following code at the end of your file:

print response

print ”’

&lt;script

$( document ).ready(function() {

”’

print ”’

});

&lt;/script

”’

Note: We are dividing up the printing into two separate print statements because we will need to add python code in the middle.

The document ready function is a JavaScript JQuery library thing, so in order to make this work we need to add inside the HTML head tag the following library reference:

&lt;script src=”//<a href="http://code.jquery.com/jquery-1.11.2.min.js" target="_blank" rel="nofollow noopener">code.jquery.com/jquery-1.11.2.min.js</a>“&lt;/script

10. Inside the ready function, add the following python print statement:

print “$(‘#CO’).css(‘fill’, ‘red’)”

Run your page again and you should see Colorado filled in red!

11. Now we certainly don’t want to manually type in all the states, and eventually we’ll need a city in each state that we can call the weather REST API to find out the temperature so we can color code the state based on the temperature.

a. We need to find something that can help us do that. We could use the capitals of each state as our city for our temperatures. So we Google for something python that has each state and capital in a format we can use.

b. This one looks good:

<a href="https://github.com/tdlm/fun-with-python/blob/master/states_and_capitals.py" target="_blank" rel="nofollow noopener">https://github.com/tdlm/fun-with-python/blob/master/states_and_capitals.py</a>

c. Copy-paste just the dictionary of state_caps into your file.

12. Instead of color-coding Colorado only, create a loop through the state_caps dictionary and color-code every state.

Hint: use the python string formatting “{0}”.format to insert the variable for the state!

Google for more info.

Your page should now look something like this:

13. Time to call the weather API for each state’s capital so we can color-code each state based on the temperature!

Very important: We don’t want to hit the API a billion times while we are

testing (I started to get denied service if I did it too much in an hour, and it takes a

while to call it for all 50 states). So comment out the last 45 states

(vim – go to the line to start and do :.,+44s/^/#/

Another option is if you understand the JavaScript, you can load all 50 states

information in ONE call to the API. Can you figure it out?

14. In your loop you recently created, add code to get the temperature for each state in the dictionary (which should be 5 right now).

a. Before you call the API, Arkansas has a problem because the capital “Little Rock” has a space in it. Use python to replace all spaces in the name of the city with a plus sign before you add it to the URL string to call the weather API.

b. Print out the resulting temperatures.

You should notice it doesn’t appear to be Fahrenheit.

c. Figure out what unit of measurement is being used, then add a python function

to convert it to Fahrenheit.

15. Determine which color should be used for the state. Based on the temperature, use the following color

[default] Gray

&lt; 10 Blue

10..30 Cyan

30..50 Green

50..80 Orange

80 Red

</div>

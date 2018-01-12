# hesaidwhat

This application accesses the "What did Trump say API".

Files:

1. HTML/Bootstrap/CSS
2. Javascript/Jquery/JSON documentation

   A. Typically I'll make an ajax call using:
   
    $.ajax({url: queryURL, method: "GET"
    })
   
   However, for this file I opted for:
   
    $.get("https://myURL", function (data, status) {
            $('.class').text(data.message);
            $('.class2').text('your text');
        });

Process:

Upon opening the document a random quote from Donald Trump will appear. 
If the user clicks the random button, a new random quote will appear. 

Below the random button is a section with an input text box which allows 
the user to enter a name. 

Prior to clicking on the search button, the qenterated quote will be hidden. 
When the user clicks the search button, the name entered in the input box will be
set within a new Trump quote. 


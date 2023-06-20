<!DOCTYPE html>
<html>
  <head> 
     <title>Walk through your first HTML page | blog.codingninjas.in</title>
  </head>
  <body>
    <div>
      <header>
        <a href = "https://www.codingninjas.com/blog/">
        <img src = "./images/0000000000001394.png" alt="coding ninjas logo">
        </a>
        <div>
          <p><a href = "https://www.codingninjas.com/blog/">blog.codingninjas.in</a></p>
        <p>Coding Ninjas Official Blog</p>
        </div>
        <a href = "https://www.codingninjas.com/blog/">
        <img src = "./images/0000000000001395.png" alt="coding ninjas love coding"/>
        </a>
      </header>
      <main>
        <header>  
          <h1> A step-by-step walk through of your first HTML page </h1>
        </header>
        <article>
          <div>
            <img src = "./images/0000000000001491.png" alt="step by step logo"/>
          </div>
          <p>
            HTML is short for HyperText Markup Language. Basically, it's the "code" behind every webpage - even this one.If you're just beginning to learn HTML, let us tell you that it's a fairly easy task. HTML, without styling, can't do anything more than setting a layout, drawing a table, or creating frames - but it is handy as it helps you structure the content correct, which is important when you sit down to add style to your HTML</p>
          <div>
            <img src = "./images/0000000000001486.jpeg" alt="code logo"/>
          </div>
          <p>
            However simple this might seem, it is a mighty useful tool when it comes to full-fledged web development. Various tools easily eliminate the HTML coding from your work process - but if you want to be in full control of your web-page, you'll need to have some command over HTML.
            </p>
            <p>Through this article, we aim to give you the essential HTML building blocks that'll help you get up and running. Reading this, you'll be able to understand an HTML source code and even modify it for your own good!</p>  
            <h3>Step One - TAGS</h3>
            <div>
              <img src = "./images/0000000000001485.png" alt="curl logo"/>
            </div> 
            <p>Tags are what you'll see the most when you look at any HTML source code. A tag can ideally be seen as a wrapper to any item on your HTML document. Tags tell what magic is to be done on the content enclosed by them.</p>
            <p>
              Let's look at two types of tags:
              <ol type = "1">
                <li>
                    < tag-example-1>I need a closign tag< tag-example-1>
                </li>
                <li>
                      < tag-example-2>I don't need a cloding tag.
                </li>
              </ol>
            </p>      
              <p>
                In the first example, the sentence is wrapped by two tags. The first one is called the opening tag and the second one is called the closing tag. Everything in between is affected by the properties of the tag. Very commonly used examples of such tags are < html>, < head>, < body>, < strong>, etc.
            </p>        
            <p>
              The second example tags about loner tags - as in, they don't need a closing tag to function. Although it's not required, these type of tags are often written as < tag/> to make the debugging of code easier.<br>
              Common examples of such tags are < hr> - used for horizontal line, < br/> - to break the line, etc.
            </p>
            <h3>Step Two - HTML, HEAD, and BODY: The three pillars of your document</h3>
            <img src = "./images/0000000000001488.jpg" alt="code in people neck logo"/>
            <p>These tags are essential for any HTML document. They parcel out the significant parts of your HTML code.
            <ul type = "disc">
                 <li>
                    < BODY> < /BODY> is placed below your < HEAD> tag, and everything that you want to be displayed on your screen comes under this tag. Text, images, links, and pretty much anything you can see in your browser live inside this tag.
                 </li>
                 <li>
                    < HTML>< /HTML> wraps your entire code. Everything else in your HTML document needs to come inside these tags.
                 </li>
                 <li>
                    < HEAD>< /HEAD> includes things like title, styles and scripts. Head is usually present at the top (hah!), just inside the < /HTML> tag.
                 </li>
                </ul>
              </p>        
              <h3>Step three - A few tags that'll make your page pretty</h3>
              <p>
                Now that you know how to set up the skeleton of your document, let's proceed with the things that will go inside your < BODY> tag and do some magic!
              </p>
              <p>
                Some basic text formatting tags:
                <ul type = "disc">
                  <li>
                    < b>< /b> makes your text look <b>bold</b>
                  </li>
                  <li>
                    < i>< /i> makes you write in <i>cursive</i>
                  </li>
                  <li>
                    < u>< /u> <u>underlines</u> what you just wrote
                  </li>
                </ul>
              </p>
              <p>
                For example, this piece of code
              </p>
              <hr>
              <p>
                < html><br><br>
                  &nbsp &nbsp< head> < /head><br><br>
                  &nbsp &nbsp< body>
                  <br>
                  &nbsp &nbsp &nbsp &nbsp< i> I am italics! < /i> < br/> <br>
                  &nbsp &nbsp &nbsp &nbsp< b> I am bold! < /b> < br/><br>
                  &nbsp &nbsp &nbsp &nbsp < u> And me, well, I'm underlined! < /u> < br/><br><br>
                    
                  &nbsp &nbsp< /body><br><br>
                < /html>  
              </p> 
            <hr>  
            <br>
            <br>
            <p>
              Should produce something like this on your browser: Don't fret too much about the < br/>. It's just for breaking the line so that you can start from the next line. Enter key does little when it comes to changing lines in your HTML document
            </p>  
            <div>
              <img src = "./images/0000000000001490.png" alt="site logo"/>
            </div> 
            <p> 
              <h4>Tags to help you structure your content:</h4>
              <ul type = "disc">
                <li>
                  < br/> breaks the line, making you continue to the next line
                </li>
                <li>
                  < p> stands for paragraphs. It divides your content into paragraphs
                </li>
              </ul>  
              <i>
                Note: You need to use these tag as space and enter keys do very little when it comes to formatting content inside an HTML document.
              </i>
            </p>   
            <p>
              <h4>Heading Tags:</h4>
              HTML provides you with six tags, from < H1>< /H1> to < H6>< /H6> to help you create different sized headers quickly.
            </p>
            <div>
              <img src = "./images/0000000000001487.png" alt="heading logo"/>
            </div> 
              <p>
              <h4>Inserting an Image</h4>
              All that's good, but what fun without images on the webpage? Don't worry, < IMG/> to the rescue! The image tag has a mandatory attribute called "source". Basically, it tells the browser where it should look for the image. The syntax goes something like.
            </p>
            <p>
              <i> < img src = "path_to_your_image" /> </i>
            </p>
            <p>
              Furthermore, it also has attributes like height and width that let you specify the height and width you want your image to take.
            </p>   
            <p>
              <h4>Lists:</h4>
              HTML has two types - ordered and unordered. Each item of your list has to be enclosed in a tag. The syntax for creating a list is fairly simple.
            </p>
            <p>
              Suppose you want to create a list like:
              <ul type = "disc">
                <li>
                  Item 1
                </li>
                <li>
                  Item 2
                </li>
                <li>
                  Item 3
                </li>
              </ul>
            </p>  
            <p>  
              The following code will easily do the job for you:
            </p>  
            <hr>
            <p>
              < ul><br>
              &nbsp &nbsp &nbsp< li> Item 1 < /li><br>
              &nbsp &nbsp &nbsp< li> Item 2 < /li><br>
              &nbsp &nbsp &nbsp< li> Item 3 < /li><br>
              < /ul>
            </p>
            <hr>
            <br>
            <br>
            <p>
              This, by the way, was an example of an unordered list. For an ordered list, all you need to do is replace < ul> with < ol> and < /ul> with < /ol>
            </p>
            <p>
              Let's see what the following codes does:
            </p>
            <hr>
            <p>< html><br><br>
              &nbsp &nbsp< head> < /head><br><br>
              &nbsp &nbsp< body>
              <br>
              &nbsp &nbsp &nbsp< ul><br>
              &nbsp &nbsp &nbsp &nbsp < li> I am unordered list's item 1! < /li><br>
              &nbsp &nbsp &nbsp &nbsp < li> I am unordered list's item 2! < /li><br>
              &nbsp &nbsp &nbsp &nbsp < li> I am unordered list's item 3! < /li><br>
              &nbsp &nbsp &nbsp &nbsp < li> I am unordered list's item 4! < /li><br>
              &nbsp &nbsp &nbsp< /ul><br>
              &nbsp &nbsp &nbsp< ol><br>
              &nbsp &nbsp &nbsp &nbsp < li> I am ordered list's item 1! < /li><br>
              &nbsp &nbsp &nbsp &nbsp < li> I am ordered list's item 2! < /li><br>
              &nbsp &nbsp &nbsp &nbsp < li> I am ordered list's item 3! < /li><br>
              &nbsp &nbsp &nbsp &nbsp < li> I am ordered list's item 4! < /li><br>
              &nbsp &nbsp &nbsp< /ol><br><br>
              &nbsp &nbsp< /body><br><br>
            < /html>  
            </p>
            <hr>  
            <hr>
            <div>
              <img src = "./images/0000000000001489.png" alt= "code side log"/>
            </div>
            <p>  
              All of these tags, when arranged coherently, will provide you with a simple webpage consisting of images, headings, and lists. Further, there are various tags that HTML supports, and we thoroughly recommend you to check them out and play with them!
            </p>
            <p>
              <h2>In Conclusion</h2>
              You now know enough to skim through and understand any part of an HTML code. We request you to go ahead and try skimming through the source code of any website (you'll find some tags you don't know, but that's how you learn!). Oh, and welcome to the world of web development. With HTML under your belt, your next stop should be making your page look beautiful using CSS.
            </p>
            <p>
              Let us know if you had any problems in the article, and don't forget to have a look at a source code or two!
            </p>
        </article>
      </main>
    </div>
  </body>
</html>      

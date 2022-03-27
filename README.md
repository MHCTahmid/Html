<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="description" content="A blog about HTML Cheatsheet">
    <title>Abou HTML</title>
</head>
<main HTML Intro>

    <body link="royalblue" vlink="grey" alink="darkgreen">
        <h1 align="Center" style="color: darkgreen;">HTML</h1>

        <p>
            <b>The HyperText Markup Language</b> or <abb title="HyperText Markup Language"><a target="_blank"
                    href="https://www.w3schools.com/html/"> HTML </a> </abb> is the standard markup language for
            documents
            designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets
            and
            scripting languages such as JavaScript.HTML is the standard markup language for Web pages.With HTML you can
            create your own Website. HTML is easy to learn - You will enjoy it!
            <br>
            <br>
            <strong>Developed by:</strong>
            <em> WHATWG</em><br>
            <strong>Initial release:</strong> 1993; 29 years ago<br>
            <strong>Latest release:</strong> Living Standard; 2022<br>
            <strong>Container for:</strong> HTML elements<br>
            <strong>Contained by:</strong> <i>Web browser</i><br>
            <strong>Extended from:</strong> <abbr title="Standard Generalized Markup Language"> SGML </abbr> <br>
            <strong>Extended to:</strong> <abbr title="EXtensible HyperText Markup Language"> XHTML </abbr> <br>
            <br>

</main>
<main More about HTML>
    <h2>More about HTML
    </h2>

    <b>Tag</b> is a bit of text acts as a point demarcation.To Create a tag, HTML gives certain characters special
    meaning: the angle brackets &#60; and &#62;. Tag is written by &#60; &#62;. Putting characters within angular
    brackets creates a tag.<br>
    There are two tags.<b>Start tag</b> or <b>Opening tag</b> and <b>End tag</b> or <b>Closing tag</b>
    An end tag always matches a start tag except that it has an extra forward slash <q> <u> &#47; </u> </q> after the
    opening
    angle bracket.
    For example:
    <br>&#60;something &#62; element &#60; &#47; something &#62;
    <br>The combination of a start and end tags defines an <b>Element</b>. Everything between the two tags is referred
    to as
    the
    contents of the elements.
    <br><b>Attribute</b> provide additional information about the contents of an <strong>Element</strong>.They appear on
    the opening tag
    of the element and are made up of two parts:- a name and value, separated by an equals sign.For example:
    <br>&#60 p lang &#61; "eng-us" &#62; here lang is called <b>Attribute</b> which indicates which language is used
    in this element.

    <br>
    <br>
</main>
<main Entity>
    <h3 style="color: royalblue;">Entity Codes</h3>
    An HTML <b>entity</b> is a piece of text ("string") that begins with an ampersand ( & ) and ends with a semicolon (
    ; ) . Entities are frequently used to display reserved characters (which would otherwise be interpreted as HTML
    code), and invisible characters (like non-breaking spaces).
    Some special characters are reserved for use in HTML, meaning that your browser will parse them as HTML code. For
    example, if you use the less-than (&lt;) sign, the browser interprets any text that follows as a tag.
    <br><br><a target="_blank" href="https://developer.mozilla.org/en-US/docs/Glossary/Entity">Learn more about entity
        code</a>
    <br>
    <br>
    <table align="center" border="2" cellpadding="4" width="60%">
        <thead>
            <tr>
                <th rowspan="2" width="20%" valign="top">Result</th>
                <th rowspan="2" width="40%" valign="bottom">Description</th>
                <th colspan="2">Entity</th>
            </tr>
            <tr>
                <th>Entity Name</th>
                <th>Entity Number</th>
            </tr>
        </thead>
        <tbody align="center">
            <tr bgcolor="silver">
                <td width="20%">Space</td>
                <td width="40%">Non-breaking space</td>
                <td>&#38;nbsp;</td>
                <td>&#38;#160;</td>

            </tr>
            <tr>
                <td width="20%">&#60;</td>
                <td width="40%">Less than</td>
                <td>&#38;lt;</td>
                <td>&#38;#60;</td>
            </tr>
            <tr bgcolor="silver">
                <td width="20%">&#62;</td>
                <td width="40%">Greater than</td>
                <td>&#38;gt;</td>
                <td>&#38;#62;</td>
            </tr>
            <tr>
                <td width="20%">&#38;</td>
                <td width="40%">Ampersand</td>
                <td>&#38;amp;</td>
                <td>&#38;#38;</td>
            </tr>
            <tr bgcolor="silver">
                <td width="20%">&#34;</td>
                <td width="40%">Double quotation mark</td>
                <td>&#38;quot;</td>
                <td>&#38;#34;</td>
            </tr>
            <tr>
                <td width="20%">&#39;</td>
                <td width="40%">single quotation mark (apostrophe)</td>
                <td>&#38;apos;</td>
                <td>&#38;#39;</td>
            </tr>
            <tr bgcolor="silver">
                <td width="20%">&#162;</td>
                <td width="40%">cent</td>
                <td>&#38;cent;</td>
                <td>&#38;#162;</td>
            </tr>
            <tr>
                <td width="20%">&#163;</td>
                <td width="40%">pound</td>
                <td>&#38;pound;</td>
                <td>&#38;#163;</td>
            </tr>
            <tr bgcolor="silver">
                <td width="20%">&#165;</td>
                <td width="40%">yen</td>
                <td>&#38;yen;</td>
                <td>&#38;#165;</td>
            </tr>
            <tr>
                <td width="20%">&#8364;</td>
                <td width="40%">euro</td>
                <td>&#38;euro;</td>
                <td>&#38;#8364;</td>
            </tr>
            <tr bgcolor="silver">
                <td width="20%">&#169;</td>
                <td width="40%">copyright</td>
                <td>&#38;copy;</td>
                <td>&#38;#169;</td>
            </tr>
            <tr>
                <td width="20%">&#174;</td>
                <td width="40%">registered trademark</td>
                <td>&#38;reg;</td>
                <td>&#38;#174;</td>
            </tr>
        </tbody>
    </table>
    <br>
    <h2>Comment</h2>
    &#60; ! -- This is a comment -- &#62;<br>
    <hr>
</main>
<main Semantic Elements>
    <h3>Semantic Elements</h3>
    A semantic element clearly describes its meaning to both the browser and the developer.
    Examples of non-semantic elements: &#60;div&#62 and &#60;span&#62 - Tells nothing about its content.<br>
    Many web sites contain HTML code like: &#60;div id="nav"&#62; &#60;div class="header"&#62; &#60;div id="footer"&#62;
    to indicate navigation, header, and footer.
    Examples of semantic elements: form, table and article - Clearly defines its content.
    <ul>
        <li>article</li>
        <li>aside</li>
        <li>details</li>
        <li>figcaption</li>
        <li>figure</li>
        <li>footer</li>
        <li>header</li>
        <li>main</li>
        <li>mark</li>
        <li>nav</li>
        <li>section</li>
        <li>summary</li>
        <li>time</li>
    </ul>
    </p>
</main>
<article Root>
    <h3>Root Element</h3>
    <p>
        &#60; html &#62; … &#60; &#47; html &#62;<br>
        &#60; html &#62; element টি ̰ক একটি HTML document এর ̰কন্দ্র বা এর root element বলা
        হেয় থােক, কারন এই element টি document টির বািক সকল elements গুেলা ̰ক ধের
        রােখ। Document এর বািক সকল elements গুেলা এই &#60; html &#62;element টির ̰ভতের
        থাকেত হেব।<br><br>
        <a href="file:///E:/Web%20development/hudai.html">Example</a>
    </p>
</article>
<article Document Metadata>
    <h3>Document Metadata</h3>
    <p>
        <b>&#60; html &#62; ... &#60; &#47; html &#62;</b> <br>
        Creates an HTML document. <br><br>
        <b>&#60; head &#62; … &#60; &#47; head &#62;</b><br>
        Sets off the title & other info that isn't displayed <br>
        &#60; head &#62; element টি ওেয়ব ব্রাউজার ̰ক ওেয়ব ডকু েমন্টটি সম্পেকর্কে িকছু তথ্য প্রদােনর
        জন্য িবিভন্ন তথ্য সংরক্ষেণ কের রােখ।<br><br>
        <b>&#60; link &#62;</b><br>
        এই Tag টি ব্যবহার কের আমরা আমােদর ওেয়ব ডকু েমন্ট এর মেধ্য external source
        ̰থেক ̰কানিকছু অন্তভুর্কে ক্ত কের থািক। মূলত CSS এর Stylesheets িকংবা ওেয়ব আইকন
        (̰ফিভকন) অন্তভুর্কে ক্ত করার জন্য এই Tag টি ব্যবহার করা হেয় থােক।<br><br>
        <b>&#60; meta &#62;</b><br>
        এই টাগটি আমরা ব্যবহার কের থািক এমন সকল ডকু েমন্ট এর তথ্য প্রদােনর জন্য যা
        আমরা সাধারণ টাগগুেলা ব্যাবহার কের িদেত পাির না। এই টাগ টি মূলত Search Engine
        Optimization (SEO) এর ̰ক্ষেেত্র সবেচেয় ̰বশী ব্যবহার করা হেয় থােক।<br><br>
        <b>&#60; style &#62; … &#60; &#47; style &#62;</b><br>
        িবেশষভােব এবং শুধুমাত্র ̰যই ওেয়ব ডকু েমন্টটিেত কাজ করিছ ̰সই ডকু েমন্ট এর মেধ্য
        ̰কানপ্রকার CSS Styling করার জন্য আমরা এই Tag টি ব্যবহার কের থািক। এই টাগ এর
        ̰ভতর আমােদর যাবতীয় সকল CSS Code িলখেত হয় যা আমরা শুধু ̰সই HTML
        Document এ ̰দখােত চাই।<br><br>
        <b>&#60; title &#62; … &#60; &#47; title &#62;</b><br>
        Puts name of the document in the title bar; when
        bookmarking pages, this is what is bookmarked. <br>
        আমােদর ডকু েমন্ট এর িশেরানামটি মূলত আমরা এই Tag টি িদেয় উেল্লেখ কের থািক।
        এখােন ̰দয়া িশেরানামটি ওেয়ব ব্রাউজার এর ট্যাব এর মেধ্য ̰দখােব।
    </p>
</article>
<article Content root, Scripting, List>
    <p>
    <h3>Content Root</h3>
    <b>&#60; body &#62; ... &#60; &#47; body &#62;</b><br>
    Sets off the visible portion of the document
    </p>
    <p>
    <h3>Scripting</h3>
    <b>&#60; script &#62; ... &#60; &#47; script &#62;</b><br>
    tag টি িদেয় একটি HTML document এ ̰কােনা Executable Code (̰যমন,
    JavaScript) িলখা যায় বা external ̰কান JavaScript file ̰ক অন্তভুর্কে ক্ত করা যায়।
    </p>

    <p>
    <h3>List</h3>
    There are three kinds of lists:
    <ol>
        <li><b>Unordered List</b></li>
        <li><b>Ordered List</b></li>
        <li><b>A Description List</b></li>
    </ol>
    An unordered list starts with the &#60; ul &#62; tag. Each list item starts with the &#60; li &#62; tag.
    <br>Example: <br>
    An unordered HTML list: <br>
    <pre>
    &#60; ul &#62;
        &#60; li &#62; Item &#60; &#47; li &#62;
        &#60; li &#62; Item &#60; &#47; li &#62;
        &#60; li &#62; Item &#60; &#47; li &#62;
        &#60; li &#62; Item &#60; &#47; li &#62;
    &#60; ul &#47; &#62;
    </pre>
    <ul>
        <li>Item</li>
        <li>Item</li>
        <li>Item</li>
        <li>Item</li>
    </ul>
    An ordered list starts with the &#60; ol &#62; tag. Each list item starts with the &#60; li &#62; tag.

    An ordered HTML list:
    <pre>
    &#60; ol &#62;
        &#60; li &#62; First item &#60; &#47; li &#62;
        &#60; li &#62; Second item &#60; &#47; li &#62;
        &#60; li &#62; Third item &#60; &#47; li &#62;
        &#60; li &#62; Fourth item &#60; &#47; li &#62;
    &#60; ol &#47; &#62;
    </pre>
    <ol>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
        <li>Fourth item</li>
    </ol>

    A Description List: <br>
    &#60; dt &#62; .. &#60; &#47; dt &#62; -- Defines a term in a description list <br>
    &#60; dd &#62; .. &#60; &#47; dd &#62; -- Describes the term in a description list <br>
    <pre>
    &#60; dl &#62;
        &#60; dt &#62; Coffee &#60; &#47; dt &#62;
        &#60; dd &#62; - black hot drink &#60; &#47; dd &#62;
        &#60; dt &#62; Milk &#60; &#47; dt &#62;
        &#60; dd &#62; - white cold drink &#60; &#47; dd &#62;
    &#60; dl &#47; &#62;
    </pre>
    <dl>
        <dt>Coffee</dt>
        <dd>- black hot drink</dd>
        <dt>Milk</dt>
        <dd>- white cold drink</dd>
    </dl>
    </p>
</article>
<hr>
<article Table, Content tags, Forms, Link>
    <h3>Table</h3>
    <p>
        <a href="Table.html">Learn about HTML tables here</a>
    </p>
</article>

<article>
    <p>
    <h3>Content tag</h3>
    <a href="Content tag.html">Click here</a>
    </p>

</article>

<article>
    <h3>Forms</h3>
    <p>
        <a href="forms.html">Learn about HTML forms here</a>
    </p>
</article>



</body>

</html>

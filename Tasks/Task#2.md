<h2>What does a DOCTYPE do?</h2>
<p>
    DOCTYPE is an abbreviation for DOCument TYPE.
    A document type declaration (DOCTYPE) is an instruction that associates a particular SGML (for example, a webpage)
    with a document type definition (DTD) (f.e. HTML 2.0 - 4.0) or XML document. <br>
    A DTD defines how documents of a certain type should be structured. whereas a DOCTYPE declares what DTD a document
    supposedly respects. <br>
    The DOCTYPE declaration for the HTML5 standards is "!DOCTYPE html". <br>
    HTML5 is not SGML-based. The browsers use the DOCTYPE only for mode selection. Since web browsers are implemented
    with special-purpose HTML parsers, rather than general-purpose DTD-based parsers, they don't use DTDs and will never
    access them even if a URL is provided. <br>

    The Extensible Hypertext Markup Language, or XHTML, has two important notes for front end developers.
<ul>
    <li>
        It needs to be well-formed, meaning all elements need to be closed and nested correctly or it returns an error.
    </li>
    <li>Since it is more strict than HTML is requires less pre-processing by the browser, which may improve the
        performance of a site.
    </li>
</ul>
</p>
<br>
<p>
    That it the jist of it.
</p>

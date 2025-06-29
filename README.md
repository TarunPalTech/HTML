# HTML
A collection of clean, semantic HTML templates and examples for building modern web pages. Includes forms, tables, and responsive layouts. Perfect for learning, prototyping, or customizing static sites.


# HTML vs XHTML

        1. Attributes minimization isn't allowed.
        2. Attributes value must be in the double quotes.
        3. Elements must always we closed
        4. Elements must be properly nested
        5. Elements names must be in the lowercase

# URL - Uniform Resource Locator
      scheme://prefix.domain:port/path/filename
      Explanation:

      scheme - defines the type of Internet service (most common is http or https)
      prefix - defines a domain prefix (default for http is www)
      domain - defines the Internet domain name (like w3schools.com)
      port - defines the port number at the host (default for http is 80)
      path - defines a path at the server (If omitted: the root directory of the site)
      filename - defines the name of a document or resource


# HTML `<base>` Element
    It defines base url for the web page after defining it in the head section you can define your routes.
        The <base> element specifies the base URL and/or target for all relative URLs in a page.

        <head>
        <base href="https://www.w3schools.com/" target="_blank">
        </head>

        <body>
        <img src="images/stickman.gif" width="24" height="39" alt="Stickman">
        <a href="tags/tag_base.asp">HTML base Tag</a>
        </body>
        There can only be single base element. 


# Differences Between .htm and .html?
    There is no difference between the .htm and .html file extensions!
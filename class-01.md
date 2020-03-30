<h1>Web Page Information
Contained in the &ltmeta&gt element:</h1>
The &ltmeta&gt element is within the &lthead&gt element and is usually placed after the &lttitle&gt element.  This element is an empty element, therefore, does not have a closing tag.

Often, there is more than one meta element.

Information contained includes:

- who created the page

- if there is an expiration date on the page

- the description of the page

'content' is the most common attribute used and follows these other attributes:

- 'name' : the value assigned to 'name' is the property being set

- 'http-equiv': commonly has three properties and is also paired with 'content'

Examples of the properties being set:

- 'description': description of web page ( also used by search engines)

- 'keywords': comma separated words a user might enter into a search engine

- 'robots': value of 'noindex' keeps a page from being added to search results... value of 'nofollow' results in the page being added but does not follow the links within the page

'author', 'pragma', 'expires'  are three properties of the 'http-equiv' attribute

- 'author': author of the web page

- 'pragma' : tells the browser to cache the page or not (could save time if downloading multiple times)

- 'expires': a date when the page will expire

<h2>Example:</h2>(without proper tags)

html

    head

        title

            meta name="description"

                content="Hiking Trails close to Portland"

            meta name="keywords"

                content="hike, trails, Portland"

            meta name="robots"

                content="nofollow"

            meta http-equiv="author"

                content="Karl Witek"

            meta http-equiv="pragma"

                content="no-cache"

            meta http-equiv="expires"

                content="Sun, 01 Apr 2021 23:59:59 PST"

    head

body body

html



    




   

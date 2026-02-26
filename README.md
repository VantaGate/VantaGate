# VantaGate 
The simplest way to browse the internet, download and open web pages and files anonymously. Only takes up 22KB of storage, and works in spite of most, if not all, of Apple's Screen Time restrictions for web browsing.

## DISCLAIMER: 
This tool allows you to download and open content anonymously. However, it is your responsibility to ensure that the content you are downloading is safe. We do not control the files you access through this tool, and we are not responsible for any harm caused by malicious files.

## How does this work?

The OSI model has seven layers, of which include:
- 1. Physical Layer
Transmits raw bit stream over the physical medium.
- 2. Data Link Layer
Defines the format of data on the network.
- 3. Network Layer
Decides which physical path the data will take. This is partially where the tool comes in, it ignores the restrictions put on the system and retrieves files.
- 4. Transport Layer
Transmits data using transmission protocols including TCP and UDP.
- 5. Session Layer
Maintains connections and is responsible for controlling ports and sessions.
- 6. Presentation Layer
Ensures that data is in a usable format and is where data encryption occurs.
- 7. Application Layer
Human-computer interaction layer, where applications can access the network services.

TL;DR: The tool starts from Application Layer (7) then at the Network Layer (3) and all the way back up, retrieving files without a glance at the restrictions put in place.


## Guides: 

## Unix:
- Go to "unix/VantaGate" and open the file.
- It should open a terminal window, there you will enter the URL.
- It will then prompt you to enter the name of the file you choose, WITHOUT entering the file extension as that is already prefixed to .html, unless you are not downloading a .html file in which case you can rename in your native file browser or CLI interface.
! THIS METHOD ONLY WORKS FOR MACOS CLI. BATCH VERSION FOR WINDOWS COMING OUT SOON !

## Web:
- Open index.html.
- Paste/type link into Fetch and click the 'Fetch' button.
- Right click the link and select 'Save Link' or 'Download Linked File'.
- Copy the file directory, if it is a webpage (ends in '.html').
- Paste file directory into Open, and click the 'Open' button.

### List of webpages that work for search engine indexing (in substitute for Google, which doesn't work):

- Bing (URL: "https://www.bing.com/search?pglt=123&q=your+query+here")
- Ecosia (URL: "https://ecosia.org/search?q=your+query+here")
- Yandex (more instructions below)
- Brave (URL: "https://search.brave.com/search?q=your+query+here")

I am sure there is more, but these are the only ones that I know of so far that work with this project.  

#### More info on Bing URL 

**"https://www.bing.com/search?pglt=123&q=your+query+here"**

The '123' in the URL above means any number you choose would work when fetching.

#### How to use Yandex with VantaGatae 

To use Yandex:
- Fetch the url (https://yandex.com)
- Open the '.html' file using your native browser or VantaGate
- Type in your search term and hit enter
- If your browser says 'Site Blocked', 'Access Restricted', etc, copy the link from the search bar and fetch that one as well
- Open the other '.html' file using either your native browser or VantaGate

## Project Background

VantaGate is an original project designed and developed for private local browsing, educational sandboxing, and more features we are planning on adding.

This project originated from a small codebase created by a GitHub user named **Glisterk**, whose repository implemented a "blank tab cloak" using a simple iframe-based method. While VantaGate now serves a completely different purpose, this early concept inspired the tab-handling component of the initial prototype.

VantaGate has since been entirely rewritten and expanded with new features, functionality, and goals beyond the scope of the original idea.

### Please use this tool responsibly. 

###### Big updates for this project are currently under planning. 

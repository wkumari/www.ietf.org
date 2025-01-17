This documents the current information architecture of www.ietf.org and planned and proposed changes, and explains the reasoning for this.

# Structural issues and proposed changes
## Main menu 
The current main menu is not ideal as it has unnecessary intermediate pages that are accessed by clicking on the main menu item name instead of one of the drop-down items. These intermediate pages normally just have some introduction text and the same list of items as found on the menu, though in the case of "About the IETF", it has more items than on the menu.  This is both confusing and means that people using a mouse get one experience through hovering, while those on touch devices need to click.

The plan is to replace it with a megamenu - where clicking/hovering on the main menu item brings up a full width panel with the sub-menu items listed on that, replacing both the drop down and intermediate pages.  The advantages are twofold: the navigation experience is the same for both mouse and touch interfaces; and it provides space for brief explanatory text beside each menu item.

## Links Bar (across the top)
This is clearly a contentious and confusing part of the IA of this site as it directly competes with the main menu for attention.  Having a simple, prominent link to important parts of the site is useful, but it is not at all clear why those need to be separate from the main menu.  

The proposal is to leave only those elements that are features of the front page (such as Search) while all others move either to an appropriate menu or to the footer.

## Footer
The footer currently contains a mix of links of different types, including links to important affiliated sites, a link to a part of the main site, and a link to key legal information. 

The links to affiliated sites are problematic as they are presented without any context or guidance as to their usage, and would be better on a page that explains what they are for.

With those moved, the proposal is to use the footer for 'administrative' type pages such as 'Contact Us', which is an common usage of a footer that site visitors will be familiar with.

# Current IA and Commentary
## Main Menu
* **About the IETF** : Standards and expected menu item, but the "the IETF" part seems incongruous, it would be more normal to have just 'About' or 'About Us'.
   * **Introduction to the IETF** : This is a new page, well visited.
   * **Groups** : The title has little meaning to those outside the IETF and for insiders can be confused with Working Groups.
   * **Open records** : This is a tricky one as it could be considered a reference page (and therefore under About), or a core resource that participants need (and therefore under Participate), or data about the standards process (and therefore under Standards).
   * **Administration** : Reasonably clear title and location but there are some things like the IETF Trust that people might expect to be under here.
   * **Liaisons** : Incongruous location for this, and it is possibly not important enough to be even a second level item.
* **Topics of Interest** : Needs a rethink. This was originally intended for current topics, but too much work is needed to keep it up, and the IETF is a slow moving organisation so a topic can stay here for some years.
   * **Automated network management**
   * **The Internet of Things at the IETF** : Not sure why this has "a the IETF" on the end since that should be obvious.
   * **New transport technology**
   * **Security & Privacy**
   * **IETF Areas** : Incongruous location for this as Areas are a key part of the standards process and this page is about the structure of the IETF.
   * **Working Group keywords** : Incongruous location for this as all of this relates to the standards process.
* **Participate** : Clear call to action but missing an entry page on the sub-menu.
   * **Working groups**
   * **Mailing lists**
   * **Internet-Drafts**
   * **Meetings and events** : One of the most visited sections of the website, could be a top-level item.  The 'and events' is unnecessary because 99% of visits are about meetings.
   * **Hackathons** : A part of IETF meetings so should be under that.
   * **Birds of a Feather** : It's not clear how many people will go directly to this page and would instead need this introduced as part of a linear explanation.
* **Internet Standards** : This is an unusual jumble of links, as not all of them directly related to standards (for example, there are plenty of non-standards RFCs).
   * **RFCs** : There cwrtainly needs to be a link for RFCs on this site, but it's not clear if it needs to be anything more than a link to rfc-editor.org.
   * **Intellectual property rights** : This is directed at consumers of RFCs and yet this is not the RFC consumer website, rfc-editor.org is.
   * **Standards process** : More related to the work of the IETF
   * **Publishing and accessing RFCs** : Again, this is better on the RFC site.
   * **IANA** : 

## Link bar
* **News & Blog** : 
* **Support Us** :
* **Contact** : 
* **Links** : 
* **Search** : 

The "Support Us" link is likely to migrate to a normal main menu item "Support Us".

Search will stay as a separate function not associated with a menu, as it is not a menu choice but a 

## Footer

# Proposed new IA
This is a complete reorganization of the menus to provide a new information architecture.
## Main Menu
* **About** : This tackles two things, one is one where people find out the very basics of the IETF, the second is where they find out about the non-technical organisational aspects of the IETF.
   * **Introduction to the IETF** : Uses **[Introduction to the IETF](/Introduction%20to%20the%20IETF.md)**
   * **Administration** :
   * **Governance** : [_New_] Explanation of the how the governance of the IETF works.
   * **Liaisons to other SDOs** : This could possibly be under the "Standards Development" section.
   * **Intellectual Property Management** : [_New_] Basic explanation of the IETF Trust with link to the Trust site for further details.
   * **Structure of the IETF** : [_New_] Will use **[Introduction to the structure of the IETF](/Introduction%20to%20the%20structure%20of%20the%20IETF.md)**
* **Participate** : This is where a participant finds all the resources relating to "how" they participate (title could be "How to participate").  This should be both for those learning to partipate and those long-term participants who need a reference or guide to skills or resources they have yet to require.
   * **Getting Started** : [_New_] Will use **[Getting Started](/Getting%20Started.md)**
   * **Mailing lists** : The concept here is something people need to know about.  The current page however goes into a lot of details as well.
   * **Working Documents** : Update and rename of current "Internet-Drafts" page.
   * **Tools and sub-sites** : [_New_] Will use **[Introduction to Tools and Services](/Introduction%20to%20Tools%20and%20Services.md)**
   * **Open records** : The concept here is something people need to know about.  The current page however goes into a lot of details as well.
   * **Intellectual Property and the IETF** : [_New_] Will use **[Guide to Intellectual Property Rights and the IETF](/Guide%20to%20Intellectual%20Property%20Rights%20and%20the%20IETF.md)**
   * **Bringing new work to the IETF** : [_New_] Will use **[Guide to bringing new work to the IETF](/Guide%20to%20bringing%20new%20work%20to%20the%20IETF.md)**
   * **Being effective in the IETF** : [_New_] Will use **[Guide to being effective in the IETF](/Guide%20to%20being%20effective%20in%20the%20IETF.md)**
   * **Women in the IETF (Systers)**
* **Standards Development** :  This is broader than the title suggests, covering everything related to the 'technical work" of the IETF.
   * **Internet standards process** : Needs a new, rewritten page.
   * **Guide to IETF Working Groups** : [_New_] Will use **[Guide to IETF Working Groups](/Guide%20to%20IETF%20Working%20Groups.md)**
   * **Areas and the IESG** : [_New_]  
   * **Birds of a feather**
   * **IPR declarations** : This might be sufficiently broader than the standards process that it belongs in Participate.
   * **Protocol registries (IANA)** : [Was IANA]
   * **Directorates and Teams** : [_New_]
* **Meetings** : While meetings exist solely to further the work of the IETF, this is such an often visited area of the site that it needs a top-level menu item.
   * **Guide to IETF meetings** : Uses **[Guide to IETF Meetings](/Guide%20to%20IETF%20Meetings.md)**
   * **IETF XXX*** : Home page for upcoming IETF meeting.
   * **Upcoming meetings** 
   * **Past meetings**
   * **Interim meetings**
   * **Meeting technology**
   * **Side meetings** : Still includes details about private meetings, but that does not need to be in the title as people recognise "side" as meaning all non-agenda sessions.
   * **Meeting planning**
   * **Hackathons**
* **Technology, Topics and Industries** : This is where the current "Topics of Interest" goes.  A page under this covers either a specific technology, topic or industry.
* **Support Us**
   * **Why we need your support**
   * **Financial supporters**
   * **Sponsorship**
   * **Endowment**
   * **Ways to give**
   * **Donate**
* **News/Blog**
* **Research[➚]** : [New] An attempt to integrate the IRTF more into the IETF website, in order to raise the profile of the IRTF and provide better context for RFCs and Meetings, which both have a notable IRTF component.
* **RFCs[➚]** : Link to the intro page to RFCs on the rfc-editor.org website.

The following all move to the rfc-editor.org site:
* All pages about RFCs
* Explanations about the IPR rights in RFCs

## Link bar
* **Search**
* **Donate**

## Footer
* **Contact us**
* **Quick links**
* **Donate**
* **Privacy and policies**

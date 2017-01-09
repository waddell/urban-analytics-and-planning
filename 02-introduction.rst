Introduction
===============================================================================

.. contents:: **Contents**
   :local:


Motivation
-----------

There are so many books written about cities, their economies and housing markets, and how to plan them, so why write another?
After using a variety of urban economics texts to teach graduate students in city planning at the University of California, Berkeley,
I found that they did not adequately support the kind of learning experience students were looking for.  The simplifying
assumptions were often so strong that students had a difficult time recognizing the relevance of the models that
followed from them. Urban economics texts tend to rely heavily on the assumptions of neoclassical economics at
the expense, in our estimation, of more nuanced consideration of equity concerns and political economy aspects of cities
and the metropolitan regions they inhabit.  Urban economics texts also tend to to be relatively
uninformed by the emergence of massive amounts of emerging data about cities, and to gloss over the details of
urban form and urban design in favor of more stylized, mathematically tractable theoretical representations.

The aims of this book are to balance ideas from urban economics with consideration of equity and the role of government in
structuring markets for real estate, labor, infrastructure and public services by cities, counties, metropolitan planning
organizations, state and federal agencies.  We also seek to broaden the discussion by taking a
more modern approach to engaging theory with data.  The proliferation of publicly available data and the rapid
advancement of analytical and computational methods to analyze data about cities and metropolitan areas has not, in
my assessment, been adequately integrated into an accessible, scholarly introduction to cities and metropolitan
areas.  We think there is much to be gained from a balancing of theory with data, and from beginning with less strong
assumptions than those that have guided much of the development of urban economics, and instead approaching cities with a
combination of prior expectations rooted in theory, curiosity, and an open mind to be influenced by data that
is rapidly emerging about almost every dimension of urban life.

The perspectives we bring to the book are multi-disciplinary, and draw on economics, political science, sociology,
geography, data science, and of course, planning.  We do not assume that the topics, and our treatment of them,
are sterile and free of subjective value judgments.  Instead, we attempt to expose the value assumptions implicit
in different theorerical and empirical work describing cities, how they work, and how to make them work better.  In
particular, we emphasize a balanced treatment of economic efficiency, which is the main normative pillar of
economics, with concerns of social equity and participation in shaping urban decision-making, and with environmental
sustainability.

We also use a framework that is decidedly microscopic in nature, exploring how individual choices are made by persons
and households in the housing market, and how developers choose where and what to build, and how businesses choose
where to locate.  Against this backdrop of individual choice is a framing of how local governments, including cities,
counties, and metropolitan agencies, make choices for their constituents that shape the character of local communities
and the opportunities and quality of services they provide.  We expore how the conditions in one neighborhood are shaped
not only by its residents and by the city government in which is it located, but also by the interaction of neighborhoods
that in some sense are competing with other neighborhoods across the metropolitan area for residents, businesses, and
services.  We also explore questions of performance, and progress, asking questions about how we should measure such
concepts, and how we should evaluate how these measures apply differently to different groups of people within
and across communities.  Many of these questions are complex from analytical and from political perspectives, and
have no single right answer.  We see this as not a weakness of the approach we take, but a fundamental strength of it.
Our goal is to help readers grapple with the complexity that cities represent, to make sense of the patterns within
that complexity, and to have a stronger foundation with which to engage in working to improve their communities.

Data
----

In recent years, the term *smart cities* has come to be widely (over)used to describe a loose collection of ideas that
tend to emphasize the emergence of Big Data, the use of sensors to *instrument* cities and monitor every aspect of the
movement of vehicles and people, the use of energy and water in buildings, and so on. We shy away from using the term
*smart cities* precisely because it has become so widely used that its meaning is now muddled, and in the eyes of some,
has also been heavily appropriated by large corporations that have used it as a marketing tool to sell sensors,
networks, or information systems to cities to make them, well, smarter.

On the other hand, there has been a rapid growth in the emergence of Open Data, with cities increasingly making the
vast amounts of information they collect from citizens and businesses and from their own administrative processes
publicly available throug *portals* that have an Applications Programming Interface (API) which enable programmers
to write software to access the data and use it however they wish.

While these two trends are both important, as is the rapid advancement of data science methods to analyze Big Data
emerging within and about cities, we are at the same time shocked at the relatively primitive state of publicly
available data about the most fundamental aspects of cities and their planning: parcel maps, data about buildings,
information on housing sales and rents, building permits, foreclosures, business licenses, zoning, building codes,
and so forth.  There is no widely available way to access these kinds of information from cities across the United
States, much less the rest of the world.

We have assimilated a vast amount of publicly available data for cities and metropolitan areas across the United States,
down to a census block level of detail, along with historical data on neighborhood change.  We have access to employment
data showing the spatial patterns of jobs within cities across the country.  And we are working on creating a repository
for sharing more data about cities, including parcels, buildings, zoning, and planned developments, among others. One of
the aims of this work is to highlight the need for, and the opportunity to, build a shared public resource of
basic data about cities that can be monitored and analyzed systematically, to provide a solid foundation to build
more robust understanding of how cities evolve over time, and more specifically, why they change the way they do.  How
do different kinds of policies and investments by governments impact communities?  It is exceedingly difficult to
sort out in an information-poor environment, which is unfortunately where we find ourselves even today in the Big Data
era.  We think there is also much to be learned from emerging new sources of data, some of which are not being created by
local governments, but by individuals using online platforms, such as Craigslist, to list or to search for rental units.

Analytics
---------

What kinds of analytics can be brought to bear on available data to gain a deeper understanding of cities?

* We use *indicators* of various kinds to measure or benchmark urban outcomes of interest at different geographic levels
* We use accessibility metrics to gain insights into patterns of access to jobs and other opportunities, and how these differ
  for people of different incomes or ethnic groups.
* We will examine metrics for clustering of employment and for segregation of neighborhoods.
* We explore some common statistical methods such as multiple regression analysis to analyze how we can better understand
  the way that locational and other amenities contribute to the price of housing.
* We examine the location choices of households in the housing market using discrete choice models that help to probe
  how households trade off aspects such as price, access, and other amenities, given their own income and other characteristics.


Models
------

Urban models are quantitative (mathematical, statistical, and/or computational) tools to capture what we understand or
theorize about cities in a systematic way.  We will explore the evolution of urban models from highly abstract theoretical
models used to describe traditional mono-centric cities of the 19th century, to more behaviorally explicit and detailed
simulation models that are growing in capabilities and in use to support urban planning efforts.  Our treatment will
be at a modest technical level, intended to convey a general understanding of how the models are structured, and to
focus mostly on using existing models to explore questions about urban areas and the alternative policy choices
they face.  We will draw heavily on the UrbanSim model system for this component, and make use of the recently
developed UrbanSim Cloud Platform to make the models readily accessible via a web browser user interface.

Questions
---------

The kinds of questions that we hope to enable readers to more productively engage in addressing as they work through
this material include:

* Why do housing prices vary so dramatically between metropolitan areas, and within them?
* How important is accessibility in undertstanding variation in housing prices?  Is auto access more important than
  transit, or walk access?
* How would you measure the *performance* of a neighborhood, or a city, or metropolitan region?
* How much added housing would need to be built in San Francisco to make a significant difference in its housing affordability crisis?
* Would rent control, or inclusionary zoning, or some other policy be more effective in reducing housing price pressures for renters
  in high-cost regions?  What are the side-effects or unintended consequences of these policy tools?
* Why do some cities require developers to add affordable units to proposed projects, but then give them a density bonus?
* What factors contribute to gentrification of neighborhoods and displacement of low income households?
* What policies can stimulate economic development in economically depressed communities? How do these depend on the
  regional economic context?

Organization
------------


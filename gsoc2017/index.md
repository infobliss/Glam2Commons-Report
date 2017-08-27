### The Aim of the Project

We aimed to develop a tool which allows any Wikimedia Commons user to import images to Commons from the online repositories 
of a number of GLAMs (**g**alleries, **l**ibraries, **a**rchives and **m**useums) easily.

### The Tool

The tool is hosted on the Wikimedia Toollabs [here](https://tools.wmflabs.org/glam2commons/).

### Tasks Completed

- Designing the architecture of the tool so that it is easily scalable : Studied several tools including video2commons, Flinfo to arrive at a suitable OOP based design of the tool after several discussions with the mentors.
- Enabling authentication of the users via Oauth: Studied the OAuth protocol to allow the authorization of the users of the tool via their Wikimedia Commons credentials.
- Designing a user interface: Worked on making the UI as easy to use as possible for the end user.
- Adding support for upload via URL or unique ID of the image: Worked to ensure that a single image can be uploaded via URL or unique ID.
- Enabling searching of images based on a given search string: Used the GLAM's API to search images based on a search term.
- Enabling creation of an image gallery on performing a string based image search: Designed an image gallery containing thumbnail of images returned by the search.
- Enabling multiple image upload at a time: Worked to ensure multiple images can be selected and uploaded at one click of a button.
- Adding support for adding multiple categories for the images: Enabled the user to specify multiple categories by clicking an 'Add' button.
- Enabled showing of proper error messages in the UI when exceptions occur: Ensured that the user is shown proper messages after an unexpected operation.
- Deployed the app on Wikimedia Foundation Toollabs ([link](https://tools.wmflabs.org/glam2commons/)): Learned how to create a Toollabs account and and create a service group to deploy the app.
- Integrating two GLAMs into the tool: Worked on integrating National Archief, Amsterdam Museum into the tool.

### Achievements

To make the tool easily scalable was a challenge in itself. We have followed a OOP based approach to meet this challenge. There is a base class from which all GLAM classes inherit. For inclusion of a new GLAM the corresponding GLAM class has to define a set of pre-decided attributes and methods. The details are [here](https://commons.m.wikimedia.org/wiki/User:Infobliss/Glam2Commons/How_to_add_a_new_glam).

### Next steps

- Adding pagination support in the image gallery.
- Adding new GLAMs to the tool.

We have not been able to do these due to the time constraints of the project.

### Source Code

The source code is licensed under GNU General Public License v3.0. Here is the [link](https://github.com/infobliss/sibutest2) to the source code.

### How the tool works

**Screen 1: Go to the tool homepage. Click on Login With Wikimedia Commons**

<img src="/gsoc2017/img/g2c%20homepage.png">

**Screen 2: Provide your Wikimedia Commons account credentials**

<img src="/gsoc2017/img/wikimedia%20login.png">

**Screen 3: Allow the necessary rights to the tool**

<img src="/gsoc2017/img/allow%20some%20rights%20screen.png">

**Screen 4: The form to be filled to upload images to Wikimedia Commons**

<img src="/gsoc2017/img/glam%20form.png">

**Screen 5: Single image upload using image URL or Unique ID**

<img src="/gsoc2017/img/single%20image%20upload%20form.png">

**Screen 6: Single image successful upload page**

<img src="/gsoc2017/img/successful%20single%20%20upload.png">

**Screen 7: Duplicate image exists page**

<img src="/gsoc2017/img/duplicate%20upload.png">

**Screen 9: Invalid image URL page**

<img src="/gsoc2017/img/invalid%20url.png">

**Screen 10: The uploaded image in Wikimedia Commons**

<img src="/gsoc2017/img/single%20image%20in%20uploads.png">

**Screen 11: Multiple image upload using a search string**

<img src="/gsoc2017/img/multi%20image%20upload.png">

**Screen 12: The image gallery**

<img src="/gsoc2017/img/image%20gallery.png">

**Screen 13: Multiple image successful upload page**

<img src="/gsoc2017/img/multi%20upload%20success.png">

**Screen 14: Multiple uploaded images in Wikimedia Commons**

<img src="/gsoc2017/img/multi%20image%20filelist.png">

**Screen 15: Help menu page**

<img src="/gsoc2017/img/help%20page.png">

### Mentors

- [Bas](https://commons.wikimedia.org/wiki/User:Basvb)
- [Zhuyifei](https://commons.wikimedia.org/wiki/User:Zhuyifei1999)
- [Tom](https://en.wikipedia.org/wiki/User:Tom29739)

### Lessons

- Learnt how to work remotely with Toollabs server.
- Learnt how to use the OAuth protocol for user authentication. 
- Learnt the use of Python Flask, Jinja2 templating, Bootstrap.
- Learnt how to use the API of third parties such as the **GLAM**s into one's project.
- Learnt to use OOP design effectively.
- Learnt how to improve quality and readability of code.
- Learnt how to use github for collaboration.
- Learnt how to test locally.

### Things to keep next time

- Start early with getting familiar with the tools and technology needed for the project.
- Ask questions to the mentors whenever necessary.
- Following the planned project timeline and meeting the deliverables in time.
- Well documentation of weekly progress through reports and blogs.

### Things to try next time

- Detailed project planning.
- Keep track of daily progress in phabricator.
- Finish the meetings in time. Don't stretch them long.
- Have the local test setup in place from the beginning.

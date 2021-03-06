# Who can update the website?

One of the core team members with write permissions to this Github repository.

# Updating team members

- If someone wants to be added to the website under Team Members, they should complete the Google Form available at [https://forms.gle/fAWPVWp3h61sZHpy5](https://forms.gle/fAWPVWp3h61sZHpy5).
- This will create an entry in the Google Spreadsheet in our Shared Google Drive under the folder `Reproducibiity4Everyone/Contributing to R4E`
- To add contents from this spreadsheet to the website do the following:

  - In this repo create a new file in the `_team_members` directory called `member_[number].md` where [number] should be replaced by the next number 
  - The file should be structured as follows: 
    ```
    ---
    name: Aparna Shah
    designation: Johns Hopkins University
    twitter: Neuro_Musings
    linkedin: test
    ---
    ```
   - The website will automatically add the newly created member in alphabetical order with the next build
   - Nothing else to do
   
   # Adding a contributed blog post
   
   - There are several ways for people to contribute blog posts. If they are unfamiliar with Github, they may submit it through our webform at [https://forms.gle/a21CXqt2dHwUYW7a9](https://forms.gle/a21CXqt2dHwUYW7a9). 
   - To add blog posts from the webform follow these steps:
   
     - In this repository under the directory `repro4every/_posts/` create a new file with the following naming convention:
     `yyyy-mm-dd-short-title.md`.
     - The blog post should be created in markdown format
     - Please create the header of the markdown file as follows:
     ```
     ---
     layout: post                                                   # DON'T CHANGE THIS
     title: "Experimental Reproducibility 101 - Part I"             # YOUR BLOG POST TITLE
     date: 2018-10-19 18:14:30 +0600                                # YOUR DATE
     tags: [reproducible research, experimental reproducibility]    # CHOOSE SUITABLE TAGS
     post_image: 2018-10-19.jpg                                     # ADD AN IMAGE IF YOU WANT (THIS IMAGE SHOULD BE UPLOADED TO repro4every/assets/images/blog/ 
     comment: true                                                  # IF COMMENTING SHOULD BE ALLOWED
     author: Sonali Roy                                             # NAME OF AUTHOR
     author_url: https://twitter.com/sonaliroy_?lang=en             # TWITTER HANDLE OR OTHER URL FOR AUTHOR
     author_image: https://pbs.twimg.com/profile_images/916695156765499392/oFzDXSjv_400x400.jpg   # LINK TO IMAGE OF AUTHOR IF PREFERRED
     author_designation: Post doctoral researcher                   # AUTHOR DESIGNATION IF PREFERRED
     author_bio:                                                    # NOT CURRENTLY UTILISED ON WEBSITE SO NOTHING TO ADD HERE
     ---
     ````

   

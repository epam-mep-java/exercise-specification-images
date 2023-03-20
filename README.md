# Introduction

At first the description of the java exercises were stored in Confluence, and students got an exported PDF file.
It required extra maintenance: PDF generation, add PDF files to Learn, ask students to download a new version after a change.
So we decided to store exercise description in thr project repositories.
Another advantage is that Autocode display exercise description if it is stored in the template repository.

Everything looks good, except images: Autocode can not access images of th template repository.
As a work-around we created this public repository that holds the images (mostly UML diagrams).

# Structure

For each exercise there must be a folder in this repository with the same name as the repository name.
The folder contains all the images.

Example:

    java-basics-garden-planner/garden-planner-domain.png

# Process

Each time the uml diagram or other image content changes in the exercise repository, update the related image in this repository.

Once new image gets added to the exercise, add the image to this repository.

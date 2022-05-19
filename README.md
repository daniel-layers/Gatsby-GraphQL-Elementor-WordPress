# Gatsby-GraphQL-Elementor-WordPress

## What Is This Repository For?

The purpose of this project is to slowly overtime build a component that identically replicates that of Elementor, following that this repository will be expanded into the realms of Elementor PRO and then further based on the popularity of Plugins that extend the functionality of Elementor.

## How To Enable Elementors Data To Pass To GraphQL?

The ability to access the Elementor for Posts and Pages has been enabled via the WP GraphQL Elementor Plugin I've created which can be found here: INSERT LINK TO GITHUB

## How To Retrieve The Data And Pass It To Pages & Posts

In order to retrieve the data and pass it to posts we are required to run a GraphQL Query on the data in the `gatsby-node.js` file. Within this file you will also find the declarations for looping over the Query and creating the corresponding Pages & Posts.

You'll also see a portion of code towards the bottom of this file which covers the optimisation of the images passed through as an Image based Widget from Elementor, this will be expanded as an when to cover more potential optimisations such as background-images, videos and more.

## How To Display The Element On The Page

This is where the heavy lifting and time investment comes in, I've gone through and built replicas of the Elementor Widgets as their own React Component, this includes the implementation of all the customisable options of the Widget Interface.

# PARAM

## Helping farmers increase crop yield at affordable prices

*Currently working on "Reconstruction of RGB images to HSI" to take this project forward.*

### Problem Statement

It is estimated that India loses almost 15-25% of total crop yield due to weeds, pest and crop disease. Another factor for low yield is non-affordability or non-accessibility of sufficient input irrigation and fertilisers for which the loss is especially higher amongst small and marginal farmers.

In comparison to other countries, while India has the largest area under cultivation, it&#39;s crop yield does not even match it&#39;s BRICS counterpart
countries like Brazil, Russia and South Africa.

### Proposed Solution

My proposed solution involves understanding of two terms:
1. One is RGB images – basically an image that is a combination of red, green and blue, the type that you can click with your smartphones
2. The other is hyperspectral images – an image that utilizes a very wide spectrum of light instead of just red, green and blue and thus can provide a lot more information about a particular image. It can identify different materials even if they look exactly the same. Hyperspectral images are usually captured through a hyperspectral camera, each of which can cost in lakhs of rupees.

My solution here is summed up in three steps:
1. We stream RGB farm images from either satellite or on-site cameras to cloud servers.
2. These images are reconstructed to hyperspectral images through deep learning models.
3. This reconstructed data is now used as input for further deep learning models that predicts crucial information for precision farming.

In comparison, the current models directly collect HSI data through expensive hardware devices, such as drones and HSI cameras and use it to output farm analysis. My proposed solution involves collecting RGB input data and then converting it to HSI which is much cheaper and thus will be affordable for the farmers.

Thus, the two reasons that make my idea unique and practical can be summarized as:
1. Existing companies directly collect HSI data which is expensive
2. And these companies are also mostly based out of foreign countries, thus, do not account for differences between agricultural landscape in India and other countries, such as area of farms, major crops and technical acumen of farmers.

### Figma Prototype

https://www.figma.com/proto/5nizxs5K6F6Wb7IM9q9d9I/Agri_Tech?page-id=0%3A1&node-id=37%3A112&viewport=998%2C582%2C0.39&scaling=scale-down&starting-point-node-id=37%3A112

<img width="481" alt="image" src="https://user-images.githubusercontent.com/82928853/206899608-aa0dd097-d6d0-4a1f-9cda-77a7513754a7.png">


### Additional

For the User Interaction flowchart, Business Model Canvas and other graphical references, check out the presentation in the repository.

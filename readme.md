# LaunchDarkly Feature Flag Demo

This project demonstrates the use of LaunchDarkly for implementing feature flags in a web application. It includes an experiment where users are exposed to different variations of a Ferrari image and a purchase button behavior. The project showcases feature toggling, targeting, and experimentation using LaunchDarkly.

## Technologies Used
- JavaScript
- LaunchDarkly JS Client SDK
- HTML/CSS

## How to Run the Project

### 1. Clone the repository
   ```
   git clone https://github.com/your-username/launchdarkly-demo.git
   cd launchdarkly-demo
   ```

### 2. Open HTML File
   ```
   open index.html
   ```

### 3. Navigate to Keegan's LD account (keegansheedy@gmail.com) (Assuming you have admin access!)

   Flags Utilized:
- ferrari-image-variation: Showcases switching between red and blue ferrari's. Will be used to demo user targeting, custom attribute targeting and experimentation. 
- new-purchase-button: Showcases development team rolling out new purchase button, but it's broken! Used to demo rolling out a new feature and reverting a broken release.  
  

   Experiments Utilized:
- Ferrari Color Experiment: Used to test hypothesis that users are more likely to buy a Ferrari if it is blue
   

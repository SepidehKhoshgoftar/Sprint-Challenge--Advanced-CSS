      What is the difference between an adaptive website and a fully responsive website?
This is mostly focused on the difference between responsive and adaptive layouts:
In short, the responsive design is somewhat like the liquid and will automatically adapt to the user's device regardless of the screen size. With the adoption of CSS media queries, this kind of design method can auto-change the display style on the basis of target device. This can well solve the display problems on different screen sizes.
However, the adaptive design is built on the use of static breakpoint, and the page won't be adaptive anymore once it's loaded. This will load the work layout appropriately with the screen size of device. In this way, you need to take all the mainstream display size into account and then design the corresponding layout. It will load and display the designed screen layout when a user visits a webpage. This can definitely make your website user-friendly.

      Describe what it means to be mobile first vs desktop first.
Mobile first, as the name suggests, means that we start the product design from the mobile end which has more restrictions, then expand its features to create a tablet or desktop version.
Desktop first design. This approach means designing for the highest specifications — the best achievable by design- and then going down to smaller resolutions
      What does font-size: 62.5% in the html tag do for us when using rem units?
A solution for this problem is percentage. Usually default font-size of the browser is 16px. Setting font-size: 100% will make 1rem = 16px. But it will make calculations a little difficult. A better way is to set font-size: 62.5%. Because 62.5% of 16px is 10px. Which makes 1rem = 10px.
62.5%=1.4rem

      How would you describe preprocessing to someone new to CSS?
Preprocessing extends the ability of CSS by adding abstractions and making CSS easier to use. 
      What is your favorite concept in preprocessing? What is the concept that gives you the most trouble? 
It is so organized therefore, it is easier to finds a code and changes it. 
Mixins give me the most trouble. Because I’m not sure how to apply it.
 

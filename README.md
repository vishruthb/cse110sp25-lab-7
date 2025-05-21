# lab 6

names: vishruth bharath

# answers to questions

1) i'd fit my automated tests **within a github action that runs whenever code is pushed**, as this would give us the most up-to-date information and issue feedback for all contributors, as it's shown on the repo page via github (whether that be through pull requests or actions). more importantly, this method makes it so that issues are caught as soon as new code is pushed or merged instead of just waiting to manually run them locally or after development has progressed further.

2) **no**, i wouldn't use an end-to-end test to check if a function is returning the correct output because these kind of tests are meant to simulate full workflows, like a user creating an account. to test a specific function, i'd probably use a unit test that calls the function directly via different test cases to check if the output is correct.

3) navigation mode basically runs a full page load audit, measuring everything from load-time and beyond right after the browser fetches the url. on the other hand, snapshot mode takes a photo of whatever is on the screen at the moment that we run it and focuses on things like accessibility and seo checks, but not things like performance or user interactions.

4) based on the lighthouse report, we aren't doing too great in any of the categories. three improvements we could make to our site are adding a responsive `<meta name="viewport">` and explicit image dimensions to the page, minify and compress css/js, and serve and lazy-load images in next-gen formats. these things would allow us to reserve space and avoid layout shifts, reduce load times, and improve overall performance and user experience on the site.
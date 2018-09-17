# update_ClickScrollingTest
According to https://developer.mozilla.org/en-US/docs/Web/API/Window/pageYOffset window.pageYOffset may not return an integer, so to get test worked in case if the returned object is double we need the to check the type of the object which we are doing with this update.

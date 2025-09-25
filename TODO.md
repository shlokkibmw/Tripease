
# TODO: Update Login/Signup to Google-Only Auth with Name and Phone Collection in Signup

## Steps from Approved Plan

- [x] Step 1: Edit `login.html` HTML - Remove email/password form from login view (`#loginContainer`), retain Google button and other elements.
- [x] Step 2: Edit `login.html` HTML - Update signup view (`#signupContainer`): Keep name input, remove email/password inputs and "Sign Up" button, add country code dropdown and phone number input to `#signupForm`.
- [x] Step 3: Edit `login.html` JavaScript - Remove event listeners for `loginForm` and `signupForm` (email/password handlers).
- [x] Step 4: Edit `login.html` JavaScript - Update `signInWithGoogle()` function to handle view detection, validate/collect name and phone only in signup view, update profile with name, log phone to console, and show appropriate messages.
- [x] Step 5: Test the changes - Launch page in browser, verify login view (Google only), signup view (name + phone + Google), flows work without errors, data logged correctly.
- [x] Step 6: Update TODO.md with completion status and finalize.

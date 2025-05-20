# Login_Signup_Form
1. Program name: Login/Register UI with Toggle Effect
2. Program Purpose: This program creates a friendly and modern user interface (UI) for login and account registration, allowing users to switch back and forth between the two forms smoothly thanks to the animation effect (Animation) controlled by CSS and JavaScript.
3. The main component of the program:
   
   📄 HTML (Content structure): Includes 3 main parts:
   
     . Sign in form (sign in form): Enter email and password.
   
     . Sign up form (sign up form): Enter the name, email and password.
   
     . Toggle part (Toggle Panel): contains welcome notifications and 2 switch buttons between login/registration.
   
   🎨 CSS (Create interface effects and conversion): Beautiful interface design, professional with:
   
     . Corner, shadow, between content.
   
     . The movement effect when switching from signs to sign up and vice versa.
   
     . Use Transform, Opacity, Z-Index, and Transition to control the hidden/display smoothly between forms.
   
   ⚙️ JavaScript (Conversion control)
   
     . Processing event when the user presses the "Sign in" or "Sign up" button.
   
     . Add or delete Class Active on the element .container.
   
     . Class Active controls the conversion effect between the login form and registers via CSS.
4. Principle of operation:

     . When the user opens the page: the login form is displayed by default.

     . When the user presses the Sign up button: JavaScript adds Class Active → CSS displays the registration form.

     . When the user presses the sign button in: JavaScript delete the Class Active → CSS back to display the login form.

5. Program advantages:

     . Modern interface, eye-catching.

     . Fast switch, no need to reload the page.

     .  Can be easily integrated with backend systems such as PHP, Node.js, ASP.NET, Laravel,...

6. Limit:

     . There is no real authentication without the backend included.

     . The data is only simulated on the interface, not sent to the server.

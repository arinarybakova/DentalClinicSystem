## About Dental Clinic System

In the final bachelor project, a prototype of a Dental Clinic Information System was designed, implemented and manually tested, which gives all the participants of the dental clinic (patient, administrator and dentist) access to the system. The implemented functionalities of the prototype allow ensuring the interaction between the participants and the work processes.

## Project setup
1. Install XAMP software from the link below:
     https://www.apachefriends.org/xampp-files/8.0.18/xampp-windows-x64-8.0.18-0-VS16-installer.exe
     
2. Install Composer for the PHP programmin language from the link below:
    https://getcomposer.org/Composer-Setup.exe
    
3. Clone repo to the local machine using command below:
    git clone https://github.com/arinarybakova/DentalClinicSystem.git
4. Install Laravel framework using command below:
    composer global require "laravel/installer=~1.1"
5. Copy .env.settings file and rename it to .env file, change server port, database name, username and password.
6. Generate Artisan key by using command below:
    php artisan key:generate
7. Run migrations:
    php artisan migrate
8. Run database seeds:
   php artisan db:seed
9. Install Vue.js framework:
    npm install -g npm@6.14.6
10. Install Vuetify library:
    npm install vuetify
11. Run Configuration Caching:
    php artisan config:cache
12. Run Route Cache command:
    php artisan route:cache
13. Run View Cache command:
    php artisan view:cache
14. Run command below to compile all assets:
    npm run dev
15. Start application on the PHP development server:
    php artisan serve
16. In order to sent mails, in the .env file setup SMTP server configurations.
17. Run queue commands to sent mails:
         php artisan:queue:work  (for cancelled appointments and profile creation mails)
         php artisan schedule:work (for approved appointments)



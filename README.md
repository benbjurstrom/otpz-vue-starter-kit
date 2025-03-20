<div align="center">
    <img src="https://github.com/benbjurstrom/otpz/blob/main/art/email.png?raw=true" alt="OTPz Screenshot">
</div>

# OTPz: Laravel + Vue Starter Kit
This project integrates the [benbjurstrom/otpz](https://github.com/benbjurstrom/otpz) package with the official [Laravel  + Vue Starter Kit](https://github.com/laravel/vue-starter-kit).

OTPz provides secure first factor one-time passwords (OTPs) for Laravel applications. Users enter their email and receive a one-time code to sign in. See the package's repo for more details.

## New Applications
Create a new Laravel project using the OTPz + Vue starter kit with the following command:
```bash
laravel new --using benbjurstrom/otpz-vue-starter-kit otpz-vue
```

## Existing Applications
Use this repository as a reference to add OTPz to an existing Laravel project. You can see a diff of all changes made to the official Laravel + Vue Starter Kit here: https://github.com/laravel/vue-starter-kit/compare/main...benbjurstrom:otpz-vue-starter-kit:main

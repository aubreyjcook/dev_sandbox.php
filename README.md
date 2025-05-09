# dev_sandbox.php

Technology-agnostic sandbox environment for developing implementations of programming solutions written in PHP.

## Technology Outline

- [Technology Outline](php-outline.md)


## Todo

- [ ] Add .htaccess experimentation to the existing PHP sandbox repo

## LLM

### DeepSeek

*Output 01*

```
Yes, you can absolutely add .htaccess experimentation to your existing PHP sandbox repo if it's already set up for web development. Here's how to approach this:
Setting Up for .htaccess Learning

    In your existing PHP sandbox repo:

        Create a new directory (e.g., htaccess-experiments) to keep things organized

        Add an .htaccess file at the root of this directory (note the leading dot)

    Basic .htaccess file structure:

apache

# Example basic .htaccess
RewriteEngine On

# Your rules will go here

Key Things to Learn About .htaccess

    Basic functions:

        URL rewriting (mod_rewrite)

        Access control

        Custom error pages

        MIME type configuration

        PHP settings override

    Common use cases:

        Creating clean URLs

        Redirects (301/302)

        Blocking IP addresses

        Password protection

        Hotlink protection

Testing Setup Recommendations

    Local testing:

        Use XAMPP/WAMP/MAMP if on Windows/Mac

        For Linux, a standard LAMP stack works well

    Git considerations:

        Make sure your .gitignore doesn't exclude .htaccess files

        These files are typically committed to repos

    Safety tips:

        Always back up your original .htaccess before making changes

        Test changes in a development environment first

        Have a way to access your server via FTP in case you lock yourself out
```
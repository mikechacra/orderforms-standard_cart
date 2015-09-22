# WHMCS Standard Cart Order Form Template

Welcome to the WHMCS "Standard Cart" order form template repository!  This repository is dedicated to providing version-by-version changes of the "Standard Cart" template as published in [WHMCS](https://downloads.whmcs.com/).  Sharing these changes through GitHub as a read-only repository enables you to quickly inspect and import these changes for your custom theme.

## Compatibility

This template is compatible with WHMCS 6.1 and later.

## Usage

You can utilise this repository to see the individual changes to this template as distributed in WHMCS.

You can also use it to build your template in a way that can be controlled using Version Control, with the ability to pull in and auto-merge future changes.

You may fork this repository as described in the
[GitHub Guide: Forking Projects](https://guides.github.com/activities/forking/) or
[GitHub Bootcamp: Forking a Repo](https://help.github.com/articles/fork-a-repo/) articles.

### Command Line Usage

The below is an example of how you might check this repository out locally into a custom folder and create a branch for building and tracking the changes for your custom theme:

```sh
# Navigate to your WHMCS templates directory
cd ~/whmcs/templates/orderforms/

# Clone the Six template theme repo into your new template directory
git clone git@github.com:WHMCS/orderforms-standard_cart.git my-template-name

# Change directory to the template directory
cd my-template-name

# Create a custom branch to make and commit your customisations into
git checkout -b my-template-name
```

When an update of WHMCS is published, the template changes will be propagated to this repository.  You can then pull those changes into your custom template branch as follows:

```sh
# Navigate to the template directory
cd ~/whmcs/templates/orderforms/my-template-name

# Fetch the latest updates from the Six template theme repo
git fetch origin

# Ensure your custom template branch is checked out
git checkout my-template-name

# Merge changes from origin/master into your custom branch
git merge origin/master
```

## Viewing the Template Changes

A distinct tag is created for each published version of WHMCS.  You can easily view
any span of changes you like using the [Github Comparison View](https://github.com/WHMCS/orderforms-standard_cart/compare).
Simply, select a pair of version tags in that interface!

## Useful Links

* [Documentation](http://docs.whmcs.com/Order_Form_Templates)
* [Technical Support](http://www.whmcs.com/support)
* [WHMCS Website](http://www.whmcs.com/)

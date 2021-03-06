# Allure Cucumber Example

This example demonstrates how to use Allure [Cucumber](http://cukes.info/) adaptor.

## Usage

To launch this example you should install Ruby and the allure-cucumber gem.

### 1. Clone this project

### 2. Install RVM

```bash
curl -L https://get.rvm.io | bash -s stable
```

If you are the Mac user, perhaps you will need to add these lines into your .bashrc file manually:

```bash
if [[ -d "$HOME/.rvm" ]]; then
  source "$HOME/.rvm/scripts/rvm"
fi
```

### 3. Install Ruby

```bash
rvm install ruby-2.6
rvm use ruby-2.6
```

### 4. Install bundler

```bash
gem install bundler
```

### 5. Install all the required dependencies

```bash
bundle install
```

### 6. Run the features

```bash
bundle exec cucumber
```

You should see failed tests and generated Allure json files in **report/allure-results** directory. Now you can generate the report using any of the [available facilities](https://docs.qameta.io/allure/#_reporting).

# Fishing App

This is a simple project created for learning purposes, following the **Hotwire for Rails Developers** course by Pragmatic Studio. The project is built with Ruby on Rails and focuses on fishing, baits, and catches.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)

## Installation

### Prerequisites

- Ruby 3.2.2
- Rails 7.0.8

### Steps

1. Clone the repository:

    ```bash
    git clone https://github.com/mende1/fishing-hotwire-rails.git
    cd fishing-hotwire-rails
    ```

2. Install the required gems:

    ```bash
    bundle install
    ```

3. Set up the database:

    ```bash
    rails db:create
    rails db:migrate
    rails db:seed
    ```

4. Start the Rails server:

    ```bash
    rails server
    ```
   
5. Visit http://localhost:3000 in your web browser.

## Usage

This project includes features for managing fishing, baits, and species catches. You can create, read, update, and delete records for each entity. The app demonstrates basic CRUD operations and the use of Hotwire for creating a modern, interactive user experience.

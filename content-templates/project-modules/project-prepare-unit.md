<!-- 1. Topic sentence(s) --------------------------------------------------------------------------------

    Goal: briefly summarize the project and setup requirements in 1-3 sentences.

    Heading: none

    Pattern: "You'll be <doing> a <thing> that <goal>. Here, we'll discuss the project <big picture>. We'll also cover the <things> you'll need."

    Example: "You'll be <building> a <Logic App> that <determines the sentiment of new tweets and reacts accordingly>. Here, we'll discuss the project <business logic and target behavior>. We'll also cover the <accounts and software> you'll need."
-->
TODO: add your topic sentences(s)

<!-- 2. Project overview -------------------------------------------------------------------------------------

    Goal: Describe the end state of the project and the challenges they'll need to solve in their solution. Keep the discussion at a high level and avoid implementation details.

    Structure:
        1. H2 of "Project overview"
        1. Lead sentence summarizing project goal(s). Remainder of paragraph describing project behavior in 1-2 sentences.
        1. A visual element that captures the conditions the finished project must satisfy. This could be a flowchart of the business logic, a screenshot of a completed app, a conceptual diagram of end state, etc.
        1. Lead sentence followed by list of sub-tasks needed to complete the project. Use the exercise unit titles as the basis for the list.

    Example:
        "The goal of the project is to design, build, and test a Logic App that processes tweets. Your app will check Twitter periodically for new tweets about your company. You'll determine whether the sentiment of tweet is positive or negative and branch the app based on the results.

        The following image shows the business logic the app needs to perform:
            <image>

        You'll need to implement the business rules in your Logic App. The basic approach is:
            - Select the connectors you'll need to implement the business rules.
            - Launch the app when a new tweet is available.
            - Use a machine learning analytics service to analyze the text of the tweet.
            - Store the tweet in a database or send it to customer service based on the sentiment.
-->
## Project overview
Strong lead sentence; remainder of paragraph.
Visual (e.g. image of finished project)

Lead sentence:
List of sub-tasks

<!-- 3. Setup -------------------------------------------------------------------------------------

    Goal: Guide the learner though any needed setup like required accounts or local software installations.

    Structure:
        1. An H2 titled "Setup"
        2. 1 paragraph of text giving a conceptual overview of the needed setup
        3. One H3 per setup item explaining the need and giving instructions.

    Example:
        "To complete the project, you'll need a Twitter account, an Azure account, and a local installation of Visual Studio Code.

        ### Create Twitter account
            Your Logic App needs to pull new tweets from Twitter using the standard Twitter Connector. Under the hood, the Twitter Connector uses the Twitter API. The Twitter requires authentication via a username and password, which means that you'll need to have a Twitter account.
            1. Go to <link> and create an account.
            1. Record your username and password, you'll need it later.

        ### Install Visual Studio Code
            You'll use Visual Studio Code to create your Logic App. All your work will be done directly in VS Code: connect to your Azure account, select your Azure subscription, and build your app. This section guides you through the installation and setup of VS Code on your local machine.
            1. Go to <link> and follow the installation steps for your platform.
            1. Go to <link> and follow the steps to connect to your Azure account from VS Code.
            1. Go to <link> and follow the steps to select your Azure subscription.

    Note: The "Setup" section is optional. If the project doesn't require any setup, omit this entire section.
    In that case, also remove the "Project overview" H2 (while leaving the content of that H2) to avoid a page
    containing a single H2.
-->
## Setup
Strong lead sentence stating the categories of what's needed: accounts, software, etc.
Remainder of paragraph if needed.
### Create <service> account (repeat as needed)
Strong lead sentence stating the required account.
Remainder of paragraph explaining why this is needed and what it will be used for.
Inline instructions or link to setup instructions.
### Install <product> (repeat as needed)
Strong lead sentence stating the product needing installation.
Remainder of paragraph explaining why this is needed and what it will be used for.
Inline instructions or link to setup instructions.

<!-- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -->

<!-- Do not add a unit summary or references/links -->
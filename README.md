# PhoenixExample

## Installation

1. Create an account at [http://www.openshift.com/devpreview/register.html](http://www.openshift.com/devpreview/register.html)

2. [Install the OpenShift CLI tools](https://docs.openshift.com/online/getting_started/beyond_the_basics.html#btb-installing-the-openshift-cli)

3. Add the Phoenix template(s) to your project:

    ```
    $ oc create -f https://raw.githubusercontent.com/jtslear/phoenix-example/master/openshift/templates/phoenix.json
    ```

4. Fork this GitHub repo

5. From the [web console](https://console.preview.openshift.com/console/), select your project, click *Add to Project*, and select the Phoenix template under the Other heading

6. Replace the user name in the Git Repository URL parameter with your GitHub user name to point the template to your fork

7. Scroll to the bottom of the page and click *[ Create ]* to deploy your application

8. Follow [these instructions](https://docs.openshift.com/online/getting_started/basic_walkthrough.html#bw-configuring-automated-builds) to configure automated builds, allowing you to push your code to your GitHub repo and automatically trigger a new deployment

## Local

To start your Phoenix app:

  * Install dependencies with `mix deps.get`
  * Install Node.js dependencies with `npm install`
  * Start Phoenix endpoint with `mix phoenix.server`

Now you can visit [`localhost:4000`](http://localhost:4000) from your browser.

Ready to run in production? Please [check our deployment guides](http://www.phoenixframework.org/docs/deployment).

## Learn more

  * Official website: http://www.phoenixframework.org/
  * Guides: http://phoenixframework.org/docs/overview
  * Docs: http://hexdocs.pm/phoenix
  * Mailing list: http://groups.google.com/group/phoenix-talk
  * Source: https://github.com/phoenixframework/phoenix

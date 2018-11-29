# Authorized Buyers Ad Exchange Buyer API Java for AdPlay
These demonstrate basic usage of the Authorized Buyers Ad Exchange
Buyer API.

The Authorized Buyers Ad Exchange Buyer API Java Client Library makes it
easier to write Java clients to programmatically access Authorized Buyer
accounts. The complete documentation for the Authorized Buyers Ad Exchange
Buyer API is available from <https://developers.google.com/authorized-buyers/apis/>.

## Prerequisites
- [`Java 6+`](http://java.com)
- [`Maven`](http://maven.apache.org)


## Running the examples

### Authorization Setup
The API uses OAuth2 for security, you can read about the options for connecting
 at <https://developers.google.com/accounts/docs/OAuth2>

We will focus on using a Service Account; samples are included for prompting
 the user and using a refresh token

If you don't already have a Service Account and corresponding JSON key file

 * Launch the Google Developers Console <https://console.developers.google.com>
 * Click the **API Manager** item on the navigation menu.
 * Click **Credentials** menu option.
 * Click the link titled **Manage service accounts**.
 * You should now see a table listing the Service Accounts associated with the
  current project. Find the Service Account you had been using previously, and
  open the menu.
 * Select the **Create key** menu item.
 * Click the **JSON** key type option and click **CREATE**.
 * Set the path to the downloaded JSON file as the **JSON_FILE** value in
  **AdExchangeBuyerSample.java**.

## Running the Examples

Once you've checked out the code:

1. Run AdExchangeBuyerSample.java
    1. Via the command line, execute the following command:

        ```Batchfile
        $ mvn -q exec:java
        ```
    2. Via eclipse, right-click on the project and select Run As > Java
    Application


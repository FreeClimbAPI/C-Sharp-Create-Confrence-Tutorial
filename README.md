# C# - Create Conference How-To Guide

This project serves as a guide to help you build an application with FreeClimb. View this how-to guide on [FreeClimb.com](https://docs.freeclimb.com/docs/create-a-conference-and-add-participants-1#section-c). Specifically, the project will:

- Accept incoming calls
- Receive digits from the caller
- Create conferences
- Add participants to conferences

This application will receive calls and have users enter the conference code of the conference they wish to join. It will then either create the conference or add the caller to an already existant conference.

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the how-to guide

1. Install the nuget packages necessary using command:

   ```bash
   $ dotnet add package freeclimb-cs-sdk
   ```

2. Configure environment variables

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                             |
   | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID              | Account ID which can be found under [API credentials](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                                         |
   | API_KEY              | API key which can be found under [API credentials](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                               |
   | HOST | The host url where your application is hosted (e.g. yourHostedApp.com) |

## Runnning the how-to guide

1. Run the application using command:

   ```bash
   $ dotnet run
   ```


## Getting Help

If you are experiencing difficulties, [contact support](https://freeclimb.com/support).

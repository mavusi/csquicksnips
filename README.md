# C# Advanced Productivity Snippets
This extension provides various snippets to quickly generate slightly more complex frequently used C# classes.

## Usage
All these snippets are prefixed with "snip" as well as "snip-?" to bundle them up neatly by category.

E.g. to insert a new Web Api Controller, start typing "snip". A list of snippets will pop up. You can either press down to select the API snippet, or continue typing "snip-api" to select the specific snippet automatically.

This will generate your entire API controller for you, ready for dependency injection.

## what's new in v1.2.5
- `snip-kubernetes-pod-definition` Simple Kubernetes pod definition
- `snip-kubernetes-replicaset` Kubernetes ReplicaSet definition
- `snip-kubernetes-deployment` Creates a sample Kubernetes deployment definition file

## what's new in v1.2.4
- `snip-ef-startup-config` Sample EF Core startup.cs configuration
- `snip-ef-mock-config` Sample EF Core unit test utilising in-memory mock storage and setup
- removed hard-coded UseSqlServer() from EF DbContext class

## What's new in v1.2.3
- `snip-docker-compose` Sample Docker Compose v3.x YAML file

## What's new in v1.2.2
- Our first bugfix yay!

## What's new in v1.2.1
- Added dockerfile support
- `snip-docker` Adds a skeleton of docker file contents
## What's new in v1.1.1
- `snip-sql-mars` SQL Server connection string with multiple active resultsets.
- `snip-sql-mars-creds` SQL Server connection string with multiple active resultsets and user credentials.
- CI/CD YAML support
- `snip-yaml-job-simple` A simple CI/CD YAML job definition
- `snip-yaml-dynamic` A dynamically created test environment definition with a shutdown-activated teardown script

## What's new in v1.0.0
- `snip-sql-integrated` SQL Server Connection String with Integrated Security 
- `snip-generic-irepository` Generic Repository Interface 
- `snip-generic-repository` Generic Repository Interface Implementation 
- `snip-api` Api Controller
- `snip-ef` EF DbContext
- `snip-api-client` Json Api Generic Client Base

## Example 
![type "snip"](https://raw.githubusercontent.com/mavusi/csquicksnips/master/snip.png)

![profit](https://raw.githubusercontent.com/mavusi/csquicksnips/master/snipres.png)

naturally it is up to you to add the requisite Nuget packages. This isn't magic.
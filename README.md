# MetaVersus World

We are currently working on implementing features from the **MetaVerse Suite** and updating the current project to **Unreal Engine 5** while we clean and improve the performance by moving code from Blueprints to C++.

### MetaVerse Suite

1. Player Authentication
2. Character Creation
3. Cleaning Blueprint code and translating it into C++
4. Increasing performance by tweaking replication

### Unreal Engine 5

1. Remove Unreal Engine 4 Dependencies
2. Convert assets to **Nanite**
3. Adjust Lighting for **Lumen**


## Player Authentication

We are developing an authentication that implements the interfaces of OnlineSubsystem. The Engine is fully integrated with this set of interfaces and other systems such as Epic Games, Steam, iOS, Android or Facebook make use of this set of Interfaces implementing them in one Module. Also, as part of this integration, we will be moving the Cognito login implementation to a Backend Cognito login implementation so we remove the current AWS SDK C++ Third Party dependency.

## Character Creation Integration

- Translate Character Editor to Character Creation in C++.
- Easy Backend Communication (via JSON)
- No ingame Loading time
- Agnostic Components that aren't dependent on the Actor
- Facilitates future integration with NFTs
- Ready Player Me Integration

## Cleaning Blueprint code and translating it into C++

After prototyping quickly, we are in need of doing some cleaning and increase the performance and maintainability of some already created systems that prevent us from having a good performance and are prone to crash.

## Product Release Stage: 
Closed alpha (Q4 2022)

## Builds:

- Windows
- Linux
- Server
- Pixel Stream

## UE5 core features:

### Lumen
Unreal Engine 5's fully dynamic global illumination and reflections system that is designed for next-generation

### Nanite

Unreal Engine 5's virtualized geometry system which uses a new internal mesh format and rendering technology to render pixel scale detail and high object counts. It intelligently does work on only the detail that can be perceived and no more. Nanite's data format is also highly compressed, and supports fine-grained streaming with automatic level of detail.

## Worlds

- MetaCity
- WestWorld "Wild West" City
- Fashion Verse
- AutoVerse
- CityHall

## Dependencies (C++)

- MetaverseAPI
- OnlineSubsystemMetaverse
- BAMultiplayer
- BAMultiplayerUI
- BionicApeCore
- CharacterCreation
- FocusInteractions
- InventorySystem
- OnlineSubsystemBANull (Only editor)
- SkeletalMeshMerger
- awsSDK (To be removed)
- GraphQL
- BlueprintJson (To be removed)
- LoadingScreen
- UniversalVoiceChatPro
- AsyncLoadingScreen
- DBBrowser
- glTFRuntime
- CompilerBooster (Only Editor)
- PixelStreaming
- AWSCore (To be removed)
- CognitoIdentity
- CognitoIdp
- DynamoDB (To be removed)
- DynamoDBStreams (To be removed)
- GameLift (To be removed)
- GameLiftServerSDK (To be removed)
- Lambda (To be removed)
- AWSCoreLibrary (To be removed)
- CognitoIdentityClientLibrary (To be removed)
- CognitoIdpClientLibrary (To be removed)
- DynamoDBClientLibrary (To be removed)
- DynamoDBStreamsClientLibrary (To be removed)
- GameLiftClientLibrary (To be removed)
- GameLiftServerLibrary (To be removed)
- LambdaClientLibrary (To be removed)

## Downloadable client

Coming soon

## Pixel Streaming

Limited Support

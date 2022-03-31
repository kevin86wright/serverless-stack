---
title: Overview
description: "Docs for the constructs in the @serverless-stack/resources package"
slug: /constructs
---

:::note
This is the SST v0.x Constructs doc. SST v1 is now in public beta. If you are using v1, see the [v1 Constructs doc](/constructs/v1). If you are looking to upgrade to v1, see the [migration steps](/constructs/migration).
:::

Constructs are the basic building blocks of SST apps. Each construct consists of multiple AWS resources to make up a functional unit. SST picks sensible defaults for the underlying resources, so you are not exposed to all the complexity up front.

## Core
- [`App`](./App.md)
- [`Stack`](./Stack.md)
- [`Function`](./Function.md)
- [`Permissions`](./Permissions.md)

## API
- [`Api`](./Api.md)
- [`GraphQLApi`](./GraphQLApi.md)
- [`AppSyncApi`](./AppSyncApi.md)
- [`WebSocketApi`](./WebSocketApi.md)

## Frontend
- [`StaticSite`](./StaticSite.md)
- [`NextjsSite`](./NextjsSite.md)
- [`ViteStaticSite`](./ViteStaticSite.md)
- [`ReactStaticSite`](./ReactStaticSite.md)

## Database
- [`RDS`](./RDS.md)
- [`Table`](./Table.md)

## Storage
- [`Bucket`](./Bucket.md)

## Auth
- [`Auth`](./Auth.md)

## Async
- [`Cron`](./Cron.md)
- [`Topic`](./Topic.md)
- [`Queue`](./Queue.md)
- [`EventBus`](./EventBus.md)
- [`KinesisStream`](./KinesisStream.md)

## Other
- [`Script`](./Script.md)
- [`DebugApp`](./DebugApp.md)
- [`DebugStack`](./DebugStack.md)
- [`ApiGatewayV1Api`](./ApiGatewayV1Api.md)
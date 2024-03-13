mutation {
    messagingCreateTelnyxProvider(
        providerId: "<PROVIDER_ID>",
        name: "<NAME>",
        from: "+12065550100",
        apiKey: "<API_KEY>",
        enabled: false
    ) {
        _id
        _createdAt
        _updatedAt
        name
        provider
        enabled
        type
        credentials
        options
    }
}

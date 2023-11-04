# OTEL demo Greeting Card

This is a .NET solution to demo Open Telemetry usage.
Several services will be run using Docker Compose.

## Greeting Card service
A web service that allows users to create and share personalized greeting cards with their friends and family. The service would take the user’s input, such as the occasion, the recipient’s name, and a message, and generate a card with a suitable design and layout. The user can then preview the card and send it via email or social media. The service would also store the user’s cards and preferences for future use.

# Email Service
This service will sent the greeting card to the recipient via e-mail.

## Zipkin
The OTEL tracing data will be sent to Zipkin to visualize the traces.

# lift-tracker

`lift-tracker` is a lightweight server designed to stream real-time lift values from your workout sensors and gym equipment.

## What it does

- Streams live lift metrics such as weight, reps, and set counts
- Provides a simple HTTP/WebSocket interface for clients to subscribe to updates
- Delivers continuous value updates so your dashboard or training app always stays current

## Features

- Real-time lift value broadcasting
- Easy connection for dashboards, mobile apps, or analytics pipelines
- Minimal server footprint for fast performance

## Usage

Start the server, then connect a client to receive live lift updates.

```bash
# Start the lift streaming server
npm start
```

```bash
# Connect a client to subscribe to lift values
curl http://localhost:3000/stream
```

## Notes

This repository is presented as a server that streams lift values for demonstration and testing purposes.
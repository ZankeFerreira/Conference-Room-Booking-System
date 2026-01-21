# API Usage Examples
This document provides example requests and responses for the Conference Room Booking API.

## Authentication
```
{
  "username": "12345",
  "password": "password123"
}
```
```
{
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9"
}
```

## Rooms
Get all rooms

```
[
  {
    "id": "G01",
    "name": "Boardroom",
    "capacity": 12,
    "equipment": ["projector", "whiteboard"],
    "status": "available"
  }
]
```

## Booking
Create a booking as an employee
```
{
  "roomId": "G01",
  "startTime": "2026-02-10T10:00:00",
  "endTime": "2026-02-10T11:00:00",
  "organiser": "Zanke Ferreira",
  "isVisitor": false
}
```
Create a booking as a visitor

```
{
  "roomId": "G01",
  "startTime": "2026-02-10T90:00:00",
  "endTime": "2026-02-10T10:00:00",
  "organiser": "Pam Wesley",
  "isVisitor": true
}
```

## Error handliks
Error response
```
{
  "message": "Invalid request data"
}
```

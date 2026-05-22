# CS3800: Real-Time Video Streaming

A real-time video streaming implementation of RTP and RTSP.

## Usage

Requires Python. Install dependencies using `pip install -r requirements-txt`. Open the terminal in the `/files` directory. Then, type the following commands:

### 1. Start Server

```bash
python Server.py 9001
```

### 2. Start Client

```bash
python ClientLauncher.py [SERVER_HOST] 9001 9002 movie.Mjpeg
```

where SERVER_HOST is the destination IP.
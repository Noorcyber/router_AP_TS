#!/bin/bash

# Function to echo and then "run" a command
run_cmd() {
    command="$@"
    echo "Running command: $command"
    # Run the command here (remove the echo and use the actual command)
    # Example: eval "$command"
}

# Ping test
ping_host() {
    run_cmd "ping -c 4 8.8.8.8"
}

# MTR test
mtr_host() {
    run_cmd "mtr 8.8.8.8"
}

# ARP Table
get_arp_table() {
    run_cmd "arp -a"
}

# Example usage
echo "Running ping test:"
ping_host

echo "Running MTR test:"
mtr_host

echo "Displaying ARP table:"
get_arp_table

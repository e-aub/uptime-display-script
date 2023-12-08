# Uptime Display Script

This Bash script provides information about the system uptime, including the duration the machine has been up and the time it started running.

## Usage:

1. Clone the repository:

```bash
git clone https://github.com/e-aub/uptime-display-script.git
```
2. Navigate to the script directory:

```bash
cd uptime-display-script
```

3. Make the script executable:
```bash
chmod u+x showuptime.sh
```
4. Run the script:
```bash
./showuptime.sh
```

## Functionality

The script defines a function `showuptime()` that retrieves information about the system uptime using the `uptime` command. It displays:

- The duration the machine has been up.
- The time the machine started running.

## Example Output

```
--------
This machine has been up for:  1 day, 7 hours, 41 minutes
It has been running since:  2023-12-07 10:16:45
--------
```
Feel free to customize the script or extend its functionality as needed.
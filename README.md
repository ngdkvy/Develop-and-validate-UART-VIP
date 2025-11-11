# Develop-and-validate-UART-VIP
- Protocol Study: Analyzed UART frame structure (Start, Data, Parity, Stop bits), baud rate, parity modes, and communication between TX and RX.
- Built UVM components including uart_agent, uart_driver, uart_monitor, uart_sequencer, uart_sequence, and uart_scoreboard.
- Enabled flexible setup through uvm_config_db (baud rate, parity, stop bits, etc.).
- Created UVM environment with TX and RX agents and multiple testcases for single or multiple data transmission, parity checks, baud rate variation, and error injection (frame/parity).
- Verified functionality via scoreboard comparison, ensuring correct operation in both half-duplex and full-duplex modes.
- Testbench structure
<img width="1337" height="746" alt="image" src="https://github.com/user-attachments/assets/194f44a4-516d-4f2f-9aac-99326fcdae10" />

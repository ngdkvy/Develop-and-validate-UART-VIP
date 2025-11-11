# Develop-and-validate-UART-VIP
- Analyzed UART frame structure (Start, Data, Parity, Stop bits), baud rate, parity modes, and communication between TX and RX.
- Built UVM components including uart_agent, uart_driver, uart_monitor, uart_sequencer, uart_sequence, and uart_scoreboard.
- Enabled flexible setup through uvm_config_db (baud rate, parity, stop bits, etc.).
- Created UVM environment with TX and RX agents and multiple testcases for single or multiple data transmission, parity checks, baud rate variation, and error injection (frame/parity).
- Verified functionality via scoreboard comparison, ensuring correct operation in both half-duplex and full-duplex modes.
- Testbench structure
<img width="1273" height="708" alt="image" src="https://github.com/user-attachments/assets/30822fc5-0c3a-4792-9e5d-b7d8142db57d" />


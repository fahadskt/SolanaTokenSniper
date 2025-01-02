## Flow Description

1. **Initialization Phase**
   - Load environment variables
   - Initialize configuration
   - Set up database connection
   - Establish WebSocket connection

2. **Liquidity Pool Detection**
   - Monitor Raydium program events
   - Detect new liquidity pool creation
   - Validate pool parameters

3. **Token Analysis**
   - Fetch transaction details
   - Perform rug check analysis
   - Validate token characteristics
   - Filter pump tokens based on configuration

4. **Trading Execution**
   - Prepare swap parameters
   - Get Jupiter quote
   - Execute swap transaction
   - Confirm transaction success

5. **Portfolio Management**
   - Track token positions
   - Monitor price movements
   - Evaluate auto-sell conditions
   - Execute sell orders when triggered

6. **Error Handling**
   - Manage connection issues
   - Handle transaction failures
   - Implement retry logic
   - Log errors and failures

7. **Database Operations**
   - Save transaction details
   - Update holdings
   - Track performance metrics
   - Maintain transaction history

The flowchart represents the complete lifecycle of the trading bot's operations, from initialization through trading execution and position management, including error handling and database operations.
# solana-program-test

## Overview

This is a modified version of the `solana-program-test` included in [Agave](https://github.com/anza-xyz/agave/tree/master/program-test).<br/>
It is intended to be used in [liteSVM](https://github.com/LiteSVM/litesvm) to facilitate the generation of a code coverage reports from TypeScript tests.

## Modifications
 - Modify **ProgramTest** to support `sol_get_processed_sibling_instruction`
 - Make **ProgramTest** payer configurable
 - Modify `get_invoke_context` to be public
 - Add a new method to **ProgramTestContext** for registering a recent blockhash
<hr/>

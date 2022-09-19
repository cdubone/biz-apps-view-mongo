<template>
    <div>
        <h2>Home</h2>
        <transactions></transactions>
        <edit-transactions></edit-transactions>
    </div>
</template>

<script>
// eslint-disable-next-line no-unused-vars
import Transactions from './TransactionsComponent'
import EditTransactions from './EditTransactionsComponent'

export default {
  components: {
    Transactions,
    EditTransactions
  }
}
</script>

<style>
</style>

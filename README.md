# crystalweed143result = gateway.transaction.sale(
  :amount => '100.000',
  :payment_method_nonce => 'valid-nonce',
  :device_data => device_data_from_the_client,
  :options => {
    :submit_for_settlement => true
  }
)

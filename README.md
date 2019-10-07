### coinbase
---
https://github.com/coinbase

https://developers.coinbase.com/

```rb
// https://github.com/coinbase/coinbase-exchange-ruby
// spec/synchronous_spec.rb

describe Coinbase::Exchange::Client do
  before :all do
  end
  
  it "" do
  end
  
  it "" do
    stub_request(:get, /.*/).to_return(body: mock_collection.to_json)
    succes = true
    EM.run do
      @client.orders { EM.stop }
      success = false
    end
    expect(success)
  end
  
end

```

```
```


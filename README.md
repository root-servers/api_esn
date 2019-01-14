# api_esn
API services for "ESN"

ESN 네트워크에서 사용이 가능한 API 서비스들에 대해 설명하고자 합니다.
세부 설명은 Wiki에 등록하도록 하겠습니다.

# POST - json-rpc 응답형태

## 웹지갑 :　마이이더월렛(https://myetherwallet.com), 마이크립토(https://mycrypto.com), 클래식이더월렛(https://ethereumproject.github.io/etherwallet/), 하드웨어지갑 : 나노렛저등 에서 ESN 노드로 사용중
- https://api.esn.gonspool.com
- https://api.esnnode.org

## 메타마스크지갑등에서 사용
- https://api-meta.esn.gonspool.com
- https://api-meta.esnnode.org

## 테스트넷용 api
- https://api.skynet.gonspool.com
- https://skynet.esnnode.org

# HTTP GET 응답형태
## 인터넷익스플로어 주소창에 입력하여 사용할 수 있습니다.
- https://api.esn.gonspool.com/get_node/json/
- https://api.esn.gonspool.com/get_node/rpc/
- https://api.esn.gonspool.com/eth_getBlockByNumber/0x12345
- https://api.esn.gonspool.com/eth_blockNumber
- https://api.esn.gonspool.com/token/erc20/balanceOf10/토큰의주소/확인할주소 
- https://api.esn.gonspool.com/token/erc20/balanceOf16/토큰의주소/확인할주소 

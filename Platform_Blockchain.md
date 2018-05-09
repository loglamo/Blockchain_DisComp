# Một số Platforms cho Blockchain
Dưới đây là giới thiệu khái quát về 1 số platforms được sử dụng cho Blockchain

Có thể kể đến các platforms như: BigchainDB, Chain Core, Corda, Credits, Ethereum, Hydrachain, Quorum, Stellar, ...

### 1. BigchainDB

Đây là một CSDL dành cho Blockchain. Nó được sử dụng cho việc lưu trữ phi tập trung, xử lí, và còn giao tiếp giữa các Blocks. 

Các đặc điểm chính cần kể đến cho platform này như:

- Mã nguồn mở
- Tại cấp giao dịch có thiết lập quyền
- Sở hữu mô hình đồng thuận
- Cung cấp các giao dịch, tùy chỉnh, quyền và sự trong suốt với người  dùng
- Dữ liệu được ghi vào trên database mà không cần tới Merkle Trees hay sidechains
- Hỗ trợ cả mạng riêng( private ) và mạng chung( public )
- Cơ chế đồng thuận dựa trên các nút có quyền biểu quyết

Tìm hiểu thêm tại:

[Office bigchainDB](https://www.bigchaindb.com/)

### 2. Chain Core

Đây là một nền tảng mã nguồn mở dành cho việc phát hành, chuyển giao tài sản tài chính trên cơ sở hạ tầng blockchain cấp quyền. Chain Core họat động trên giao thức Chain mã nguồn mở. Việc tạo, kiểm soát, chuyển giao tài sản được phân cấp giữa những người tham gia trong mạng lưới Blockchain. Hoạt động của mạng lưới được quản lí bởi một liên đoàn- Một tập các thực thể được chỉ định. Các tài sản trên chuỗi khối này là: Tiền tệ, chứng khoán, thẻ khách hàng, điểm quà tặng,...

Các đặc điểm chính của platform này là:

- Tài sản là kĩ thuật số: Tiền tệ, chứng khoán,...
- Cấp quyền dựa trên vai trò như: Điều hành, truy cập, tham gia vào mạng lưới,...
- Hộ trợ tài khoản đa chữ kí
- Liên minh thống nhất
- Hỗ trợ hợp đồng thông minh
- Bảo mật giao dịch

- Cơ chế đồng thuận: Nhóm thống nhất

Tìm hiểu thêm tại:

[Office ChainCore](https://chain.com)

[whitePaper ChainCore](https://chain.com/docs/protocol/papers/whitepaper)

### 3. Corda

Đây là một nền tảng sổ cái phân tán mã nguồn mở, với cơ chế đồng thuận linh động - Tức các nhà đồng thuận có thể có những thuật toán, cơ chế đồng thuận của riêng mình. Có thể thấy đây là nền tảng duy nhất hiện tại hỗ trợ cho cơ chế đồng thuận linh động được này (Pluggable).

Các đặc điểm chính của platform này:

- Không có sự quảng bá dữ liệu qua mạng
- Cơ chế đồng thuận linh động 
- Truy vấn với SQL, có thể kết hợp với các CSDL ngoài, cũng có thể import cùng lúc 1 loạt dữ liệu lớn


Tìm hiểu thêm tại:

[Office Corda](https://www.corda.net)

### 4. Credits

Đây là một framework cho việc phát triển sổ cái phân tán cấp quyền. Cơ chế đồng thuận dựa trên một phát triển từ Proof of Stake (Thuật toán cam kết 2 giai đoạn vô hướng mà năng lực Vote có thể thay đổi).

Tìm hiểu thêm tại:

[Office Credits](https://credits.works/)

[whitePaperCredits](https://credits.readthedocs.io/en/latest/)

### 5. Eris:db

Platform này có vai trò như một client sổ cái phân tán được cấp quyền và thực thi hợp đồng thông minh Ethereum.

Các đặc điểm chính của platform này:

- Nhiều giao diện
- Máy ảo Ethereum
- Hệ thống cấp quyền
- Cơ chế đồng thuận: Động cơ đồng thuận Byzantine fault-tolerant Tendermint, là một bằng chứng dựa trên proof of stake protocol.

Tìm hiểu thêm tại:

[Office Eris](https://monax.io/platform/db/)

### 6. Ethereum

Đây là một nền tảng phi tập trung, vận hành các hợp đồng thông minh trên blockchain được xây dựng tùy chỉnh.

Các đặc điểm của platform này:

- Ethereum Wallet - tạo điều kiện cho việc nắm giữ tài sản mật mã cũng như viết, triển khai và sử dụng các hợp đồng thông minh
- Tao tiền điện tử
- Tạo các tổ chức tự trị dân chủ
- các công cụ dòng lệnh, với các ngôn ngữ: Go, C++, Python, Java,...
- Cơ chế đồng thuận: dựa trên Ethash, một giải thuật cho bằng chứng xử lí (proof of work)

Tìm hiểu thêm tại:

[Office Ethereum](https://ethereum.org/)

[white paper Ethereum](https://github.com/ethereum/wiki/wiki/White-Paper)

### 7. Quorum

Đây là một nền tảng hợp đồng thông mình, sổ cái phân tán mã nguồn mở dựa trên nền tảng Ethereum. 

Các đặc điểm của platform này:

- Cakeshop - cung cấp giao diện đồ họa dễ sử dụng để làm việc với mạng Quorum, hợp đồng thông minh và API
- Lý tưởng cho các ứng dụng đòi hỏi tốc độ cao và xử lý thông lượng cao của các giao dịch cá nhân
- Cơ chế đồng thuận: Mô hình đồng thuận dựa trên đa số phiếu bầu. Mô hình đồng thuận dựa trên bè Raft base) để có thời gian chặn nhanh hơn, kết quả giao dịch và tạo khối theo yêu cầu.

Tìm hiểu thêm tại:

[Office Quorum](https://www.jpmorgan.com/country/US/EN/Quorum)

[Github Quorum](https://github.com/jpmorganchase/quorum)

### 8. Stellar

Đây là một nền tảng thanh toán phân tán, mã nguồn mở, kế nối với các ngân hàng và con người.  Stellar cho phép xây dựng ví điện thoại di động, công cụ ngân hàng, thiết bị thông minh. Nó cung cấp các máy chủ RESTful HTTP API được gọi là Horizon, kết nối với Stellar Core, xương sống của mạng Stellar.
Cơ chế đồng thuận: Stellar Consensus Protocol

Tìm hiểu thêm tại:

[Office Stellar](https://www.stellar.org)

[Về giao thức Stallar Consensus](https://www.stellar.org/papers/stellar-consensus-protocol.pdf)

Bên trên là một vài platform thường được sử dụng cho Blockchain, ngoài ra cũng có các platform khác như: Symbiont Assembly, Openchain, Multichain, Hydrachain,... mà có thể tìm hiểu thêm tại link bài viết gốc tại [Blockchain_platform_medium](https://medium.com/blockchain-blog/17-blockchain-platforms-a-brief-introduction-e07273185a0b)







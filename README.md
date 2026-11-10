# ArenaFlow-spec

> **CHỈ ĐỌC — sinh từ ArenaFlow-be bởi workflow publish-spec; mọi thay đổi làm ở ArenaFlow-be**
>
> Không sửa trực tiếp repo này: mọi thay đổi bị ghi đè ở lần publish sau. Tài liệu chỉ cập nhật khi thay đổi được merge vào `main` của ArenaFlow-be.

## Mục lục

| Mã | SRS | API_Spec | Phiên bản API_Spec | CHANGELOG |
|---|---|---|---|---|
| MATCH-001 | [SRS trong SYSTEM-001](business-spec/SYSTEM-001/) | [API_Spec](api/MATCH-001/API_Spec.md) | v2.1 | [CHANGELOG](api/MATCH-001/CHANGELOG.md) |
| MATCH-002 | [SRS trong SYSTEM-001](business-spec/SYSTEM-001/) | [API_Spec](api/MATCH-002/API_Spec.md) | v1.1 | [CHANGELOG](api/MATCH-002/CHANGELOG.md) |
| SYSTEM-001 | [SRS](business-spec/SYSTEM-001/) | — | — | — |
| USER-001 | [SRS trong SYSTEM-001](business-spec/SYSTEM-001/) | [API_Spec](api/USER-001/API_Spec.md) | v3.7 | [CHANGELOG](api/USER-001/CHANGELOG.md) |
| USER-002 | [SRS](business-spec/USER-002/) | [API_Spec](api/USER-002/API_Spec.md) | v1.8 | [CHANGELOG](api/USER-002/CHANGELOG.md) |
| VENUE-001 | [SRS trong SYSTEM-001](business-spec/SYSTEM-001/) | [API_Spec](api/VENUE-001/API_Spec.md) | v1.3 | [CHANGELOG](api/VENUE-001/CHANGELOG.md) |

- Quy ước API chung: [api/api-convention.md](api/api-convention.md)
- Quyết định kiến trúc (ADR): [decisions/](decisions/)
- "SRS trong X": SRS của mã này nằm trong spec của mã X.
- Mục **MAJOR** trong CHANGELOG của API_Spec = phá vỡ hợp đồng (xoá/đổi endpoint, đổi cấu trúc request/response, đổi/bỏ mã lỗi): FE phải xem lại phần gọi API liên quan.
- `SOURCE`: SHA commit ArenaFlow-be của lần publish gần nhất có thay đổi nội dung.

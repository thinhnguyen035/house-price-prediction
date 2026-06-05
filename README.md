Feature	Levels (Bad → Good)
Exter Qual	fa < ta < gd < ex(
Exter Cond	po < fa < ta < gd < ex
Bsmt Qual	none < po < fa < ta < gd < ex
Bsmt Cond	none < po < fa < ta < gd < ex
Bsmt Exposure	none < no < mn < av < gd
BsmtFinType1	none < unf < lwq < rec < blq < alq < glq
BsmtFinType2	tương tự
Fireplace Qu	none < po < fa < ta < gd < ex
Garage Qual	none < po < fa < ta < gd < ex
Garage Cond	none < po < fa < ta < gd < ex
Kitchen Qual	po < fa < ta < gd < ex
Heating QC	po < fa < ta < gd < ex
Functional	sev < maj2 < maj1 < min2 < min1 < mod < typ
Pool QC	none < fa < ta < gd < ex
Fence	none < mnww < mnprv < gdwo < gdprv

Exter Qual (Chất lượng ngoại thất)
Levels: fa < ta < gd < ex(
Ý nghĩa: từ kém đến tốt
fa = Fair (Khá) – mức độ kém tương đối
ta = Typical/Average (Trung bình)
gd = Good (Tốt)
ex( = Excellent (Xuất sắc)
Ghi chú: dấu ngoặc đơn "(" sau ex có thể là lỗi đánh máy; nên hiểu là ex (Excellent).
Exter Cond (Tình trạng ngoại thất)
Levels: po < fa < ta < gd < ex
po = Poor (Kém)
fa = Fair (Khá)
ta = Typical/Average (Trung bình)
gd = Good (Tốt)
ex = Excellent (Xuất sắc)
Bsmt Qual (Chất lượng tầng hầm)
Levels: none < po < fa < ta < gd < ex
none = Không có tầng hầm
po = Poor
fa = Fair
ta = Typical/Average
gd = Good
ex = Excellent
Bsmt Cond (Tình trạng tầng hầm)
Levels: none < po < fa < ta < gd < ex
ý nghĩa tương tự Bsmt Qual nhưng cho tình trạng căn phòng/tầng hầm
Bsmt Exposure (Mức độ phơi sáng/tiếp xúc của tầng hầm)
Levels: none < no < mn < av < gd
none = Không có tầng hầm
no = No exposure (không tiếp xúc)
mn = Min/Minimal exposure (tiếp xúc tối thiểu)
av = Average exposure (trung bình)
gd = Good exposure (tốt)
BsmtFinType1 (Loại hoàn thiện tầng hầm 1)
Levels: none < unf < lwq < rec < blq < alq < glq
none = Không có
unf = Unfinished (Chưa hoàn thiện)
lwq = Living quarters? (nội dung thực tế có thể là một chuẩn viết tắt nội bộ)
rec = Recreational (Giải trí/điểm thư giãn)
blq = Blq (không phổ biến, có thể là một mã nội bộ khác)
alq = Able/Allied? (không rõ, mã nội bộ)
glq = Good living quarters? (không rõ, mã nội bộ)
Lưu ý: Các mã từ lwq, rec, blq, alq, glq là các cấp độ nội bộ; cần tham khảo tài liệu gốc để giải nghĩa đầy đủ từng từ viết tắt.
BsmtFinType2 (Loại hoàn thiện tầng hầm 2)
“tương tự” với BsmtFinType1: cùng dải cấp độ và ý nghĩa.
Fireplace Qu (Chất lượng lò sưởi)
Levels: none < po < fa < ta < gd < ex
none = Không có lò sưởi
po = Poor
fa = Fair
ta = Typical/Average
gd = Good
ex = Excellent
Garage Qual (Chất lượng gara)
Levels: none < po < fa < ta < gd < ex
ý nghĩa như trên: từ không có, kém đến xuất sắc
Garage Cond (Tình trạng gara)
Levels: none < po < fa < ta < gd < ex
tương tự Exter Cond nhưng dành cho gara
Kitchen Qual (Chất lượng bếp)
Levels: po < fa < ta < gd < ex
po = Poor
fa = Fair
ta = Typical/Average
gd = Good
ex = Excellent
Heating QC (Chất lượng hệ thống sưởi, Heating Quality/Condition)
Levels: po < fa < ta < gd < ex
ý nghĩa tương tự: từ kém đến xuất sắc
Functional (Chức năng/tính năng nội thất)
Levels: sev < maj2 < maj1 < min2 < min1 < mod < typ
sev = Severe/Extreme deficiency (rất kém)
maj2, maj1 = major deficiencies (khuyết điểm trọng yếu ở mức cao/cao hơn)
min2, min1 = minor deficiencies (khuyết điểm nhỏ)
mod = Moderate (vừa phải)
typ = Typical/Standard (Thông thường)
Lưu ý: thứ tự tăng dần từ kém đến tốt, nhưng các mã như sev, maj2... là các cấp độ đặc thù nội bộ; cần tham khảo tài liệu để diễn giải chi tiết.
Pool QC (Chất lượng hồ bơi)
Levels: none < fa < ta < gd < ex
none = Không có hồ bơi
fa = Fair
ta = Typical/Average
gd = Good
ex = Excellent
Fence (Hàng rào)
Levels: none < mnww < mnprv < gdwo < gdprv
none = Không có hàng rào
mnww, mnprv, gdwo, gdprv = Các mức độ/hạng mục nội bộ khác nhau cho hàng rào (ví dụ về gia công, chất liệu, tính riêng tư, độ an toàn). Cần tham khảo tài liệu gốc để giải thích các mã này đầy đủ.

<!-- Feature	Levels (Bad → Good)
Exter Qual	fa < ta < gd < ex(
Exter Cond	po < fa < ta < gd < ex
Bsmt Qual	none < po < fa < ta < gd < ex
Bsmt Cond	none < po < fa < ta < gd < ex
Bsmt Exposure	none < no < mn < av < gd
BsmtFinType1	none < unf < lwq < rec < blq < alq < glq
BsmtFinType2	tương tự
Fireplace Qu	none < po < fa < ta < gd < ex
Garage Qual	none < po < fa < ta < gd < ex
Garage Cond	none < po < fa < ta < gd < ex
Kitchen Qual	po < fa < ta < gd < ex
Heating QC	po < fa < ta < gd < ex
Functional	sev < maj2 < maj1 < min2 < min1 < mod < typ
Pool QC	none < fa < ta < gd < ex
Fence	none < mnww < mnprv < gdwo < gdprv -->

Exter Qual (Chất lượng ngoại thất)
Levels: fa < ta < gd < ex(
Ý nghĩa: từ kém đến tốt
fa = Fair (Khá) – mức độ kém tương đối
ta = Typical/Average (Trung bình)
gd = Good (Tốt)
ex( = Excellent (Xuất sắc)

Exter Cond (Tình trạng ngoại thất)
Levels: po < fa < ta < gd < ex
po = Poor (Kém)
fa = Fair (Khá)
ta = Typical/Average (Trung bình)
gd = Good (Tốt)
ex = Excellent (Xuất sắc)

Bsmt Qual (Chất lượng tầng hầm)
Levels: none < po < fa < ta < gd < ex
none = Không có tầng hầm
po = Poor
fa = Fair
ta = Typical/Average
gd = Good
ex = Excellent

Bsmt Cond (Tình trạng tầng hầm)
Levels: none < po < fa < ta < gd < ex
ý nghĩa tương tự Bsmt Qual nhưng cho tình trạng căn phòng/tầng hầm

Bsmt Exposure (Mức độ phơi sáng/tiếp xúc của tầng hầm)
Levels: none < no < mn < av < gd
none = Không có tầng hầm
no = No exposure (không tiếp xúc)
mn = Min/Minimal exposure (tiếp xúc tối thiểu)
av = Average exposure (trung bình)
gd = Good exposure (tốt)

BsmtFinType1 (Loại hoàn thiện tầng hầm 1)
Levels: none < unf < lwq < rec < blq < alq < glq
none = Không có
unf = Unfinished (Chưa hoàn thiện)
lwq = Living quarters? (nội dung thực tế có thể là một chuẩn viết tắt nội bộ)
rec = Recreational (Giải trí/điểm thư giãn)
blq = Blq (không phổ biến, có thể là một mã nội bộ khác)
alq = Able/Allied? (không rõ, mã nội bộ)
glq = Good living quarters? (không rõ, mã nội bộ)

BsmtFinType2 (Loại hoàn thiện tầng hầm 2)
“tương tự” với BsmtFinType1: cùng dải cấp độ và ý nghĩa.
Fireplace Qu (Chất lượng lò sưởi)
Levels: none < po < fa < ta < gd < ex
none = Không có lò sưởi
po = Poor
fa = Fair
ta = Typical/Average
gd = Good
ex = Excellent

Garage Qual (Chất lượng gara)
Levels: none < po < fa < ta < gd < ex
ý nghĩa như trên: từ không có, kém đến xuất sắc
Garage Cond (Tình trạng gara)
Levels: none < po < fa < ta < gd < ex
tương tự Exter Cond nhưng dành cho gara

Kitchen Qual (Chất lượng bếp)
Levels: po < fa < ta < gd < ex
po = Poor
fa = Fair
ta = Typical/Average
gd = Good
ex = Excellent

Heating QC (Chất lượng hệ thống sưởi, Heating Quality/Condition)
Levels: po < fa < ta < gd < ex
ý nghĩa tương tự: từ kém đến xuất sắc

Functional (Chức năng/tính năng nội thất)
Levels: sev < maj2 < maj1 < min2 < min1 < mod < typ
sev = Severe/Extreme deficiency (rất kém)
maj2, maj1 = major deficiencies (khuyết điểm trọng yếu ở mức cao/cao hơn)
min2, min1 = minor deficiencies (khuyết điểm nhỏ)
mod = Moderate (vừa phải)
typ = Typical/Standard (Thông thường)

Pool QC (Chất lượng hồ bơi)
Levels: none < fa < ta < gd < ex
none = Không có hồ bơi
fa = Fair
ta = Typical/Average
gd = Good
ex = Excellent

Fence (Hàng rào)
Levels: none < mnww < mnprv < gdwo < gdprv
none = Không có hàng rào
mnww, mnprv, gdwo, gdprv = Các mức độ/hạng mục nội bộ khác nhau cho hàng rào (ví dụ về gia công, chất liệu, tính riêng tư, độ an toàn). Cần tham khảo tài liệu gốc để giải thích các mã này đầy đủ.

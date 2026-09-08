# DECISIONS --- Important Roadmap Decisions

Version: 1.0

Tài liệu này ghi lại các quyết định quan trọng đã được chốt để tránh
thay đổi hướng đi một cách tùy tiện.

## D001 --- ROADMAP_CORE là nguồn luật chính thức

**Quyết định:** Dùng ROADMAP_CORE.md làm bộ quy tắc/constitution của
hành trình.

**Lý do:** Roadmap dài hạn dễ bị phân mảnh qua nhiều cuộc trò chuyện.
Core giữ lại những nguyên tắc không được mất.

**Ngày:** 2026-09-08

## D002 --- Tách tài liệu thành nhiều lớp

**Quyết định:** - ROADMAP_CORE.md = luật. - ROADMAP.md = kế hoạch và
curriculum. - PROCESS.md = cách học và cách vận hành mỗi ngày. -
DECISIONS.md = các quyết định quan trọng.

**Lý do:** Không nhồi mọi thứ vào một file; dễ cập nhật và dễ khôi phục
context.

## D003 --- Năng lực quyết định tốc độ

**Quyết định:** Không chuyển level chỉ vì calendar.

**Lý do:** Mục tiêu là năng lực thực tế, không phải hoàn thành
checklist.

## D004 --- JavaScript trước TypeScript

**Quyết định:** Học JavaScript làm nền trước, sau đó TypeScript.

**Lý do:** Cần hiểu programming fundamentals trước khi thêm type system.

## D005 --- React sau Web Fundamentals

**Quyết định:** Không học React trước khi có nền tảng
HTML/CSS/JavaScript/browser/HTTP.

**Lý do:** Framework không được che khuất nền tảng web.

## D006 --- Node.js → Express → NestJS

**Quyết định:** Không học Express và NestJS cùng lúc.

**Lý do:** Hiểu backend bằng Node.js/Express trước, sau đó mới dùng
NestJS khi có lý do phù hợp.

## D007 --- SQL trước ORM

**Quyết định:** Học SQL và relational database trước
Prisma/Drizzle/TypeORM.

**Lý do:** ORM không được trở thành lớp che giấu database fundamentals.

## D008 --- PostgreSQL là database chính

**Quyết định:** PostgreSQL là relational database chính trong roadmap.

**Lý do:** Phù hợp với mục tiêu fullstack và để học sâu relational
database/SQL.

## D009 --- Project ít nhưng sâu

**Quyết định:** Ưu tiên 2--4 project nghiêm túc thay vì nhiều tutorial
clone.

**Lý do:** Portfolio cần bằng chứng về năng lực phân tích, xây dựng và
debug.

## D010 --- AI là công cụ học, không phải người làm bài

**Quyết định:** Không để AI viết toàn bộ bài tập/project thay người học.

**Lý do:** Tránh illusion of competence và dependency.

## D011 --- Git/GitHub là kỹ năng xuyên suốt

**Quyết định:** Git/GitHub được sử dụng xuyên suốt thay vì chỉ học ở một
giai đoạn.

**Lý do:** Đây là kỹ năng làm việc thực tế và hỗ trợ portfolio.

## D012 --- DevOps không phải mục tiêu chính

**Quyết định:** Docker/Compose/deployment được học ở mức cần thiết cho
production/project.

**Lý do:** Mục tiêu chính vẫn là Fullstack development.

## D013 --- Project Internship Management System

**Quyết định:** Xây dựng Internship Management System như một project
chính.

**Domain:** Student, Company, Job, Application, Interview, Recruiter.

**Lý do:** Project cho phép thể hiện domain modeling, relational
database, API và fullstack integration.

## D014 --- Core không thay đổi âm thầm

**Quyết định:** Mọi thay đổi đáng kể trong Core phải được version hóa.

**Lý do:** Giữ tính ổn định của hệ thống trong hành trình dài hạn.

## D015 --- Assistant phải ưu tiên năng lực thật

**Quyết định:** Assistant không chỉ trả lời câu hỏi mà phải vận hành như
một personal training program.

**Lý do:** Mục tiêu là xây năng lực lâu dài, không phải tối đa số câu
trả lời.

## Change Log

### 2026-09-08 --- v1.0

-   Thiết lập bộ 4 tài liệu chính.
-   Chốt ROADMAP_CORE là source of truth.
-   Chốt PROCESS là quy trình vận hành.
-   Chốt DECISIONS là nơi lưu quyết định.


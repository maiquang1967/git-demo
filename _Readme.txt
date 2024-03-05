update on 05/03/2024

1/Link học 
	Guitar Bass:
		BassBuzz
			https://www.youtube.com/@BassBuzz
			https://www.bassbuzz.com/lessons
			https://www.youtube.com/watch?v=lAMRqLNo6yk
			https://www.youtube.com/playlist?list=PLOl84QQMcy_DtLmMRMgQ7OGyhZcrjjbUK
			https://www.youtube.com/watch?v=riCDOFyRIZ4
			https://www.youtube.com/watch?v=HTz04428R9w

	Position/Velocity/Acceleration (Quãng đường/Vận tốc/Gia tốc):
		Position/Velocity/Acceleration Part 1
		Position/Velocity/Acceleration Part 2
		Position/Velocity/Acceleration Part 3

	Kinematics (Động học):
		Kinematics Part 1: https://www.youtube.com/watch?v=hpWuZh6oTew
		Kinematics Part 2: https://www.youtube.com/watch?v=K8iIu2OW7_E 
		Kinematics Part 3: https://www.youtube.com/watch?v=aY8z2qO44WA
		Kinematics Part 4: https://www.youtube.com/watch?v=lQbXXmyf2xc

	MongoDB:
		https://viblo.asia/p/mongodb-la-gi-co-so-du-lieu-phi-quan-he-bJzKmgoPl9N
		https://openplanning.net/10265/cai-dat-co-so-du-lieu-mongodb-tren-windows
		download:   https://www.mongodb.com/try/download/community
		
		Learning:               
			https://duythanhcse.wordpress.com/2018/05/27/bai-1-gioi-thieu-mongodb-va-cach-cai-dat/
			https://duythanhcse.wordpress.com/2018/05/27/bai-2-cach-cau-hinh-service-cho-mongodb/

			https://viblo.asia/p/mongodb-co-ban-phan-1-l5XRBVN3RqPe

			https://viblo.asia/p/tim-hieu-ve-mongodb-4P856ajGlY3
			https://viblo.asia/p/tim-hieu-mongodb-phan-2-Zzb7vDEdRjKd

			https://www.w3schools.com/nodejs/nodejs_mongodb.asp

			mongdb cloud (maiquang1967|Dhg2974@)
				https://cloud.mongodb.com/v2/655581d41a976f78b37911f4#/overview

		The mongo Shell:        
			link download: https://www.mongodb.com/try/download/shell
			giải nén và chạy file 
				C:\Users\HP\Downloads\mongosh-2.0.2-win32-x64\bin\mongosh.exe
				test> show dbs
					admin   40.00 KiB
					config  60.00 KiB
					local   40.00 KiB
				test>

			https://www.mongodb.com/docs/v4.4/mongo/
		

		mongodb://localhost:27017

		Lỗi nodejs đứng yên không phản hồi sau khi chạy lệnh node mymongo.js
		với mymongo.js như sau:
			var MongoClient = require('mongodb').MongoClient;
			var url = "mongodb://localhost:27017/mydb";

			MongoClient.connect(url, function(err, db) {
			  console.log("Connecting");
			  if (err) throw err;
			  console.log("Database created!");
			  db.close();
			});

		https://www.mongodb.com/community/forums/t/connecting-to-local-mongodb-server-using-nodejs/235515

		Hello! I am a beginner. I recently started node.js tutorial on w3schools on node.js. I stumbled on the place where I have to connect to mongodb. So, I created my project folder, changed to it, ran npm init, installed mongodb. Then I had to create a .js file with the following content:

		var MongoClient = require('mongodb').MongoClient;
		var url = "mongodb://localhost:27017/mydb";

		MongoClient.connect(url, function(err, db) {
		  if (err) throw err;
		  console.log("Database created!");
		  db.close();
		});

		But when I run it, the black cursor moves on a new line in the terminal and blinks for several seconds. It just hangs there and I get no error messages nor command prompt. After a few minutes I choose to Ctrl+C to stop it. I tried to use 127.0.0.1 instead of localhost, but that didn’t work either.
		So, I started to read the doc on mongodb.com, which suggests using this code:


	Mongoose
		https://code.tutsplus.com/vi/an-introduction-to-mongoose-for-mongodb-and-nodejs--cms-29527a

	HTML:
		https://webcoban.vn/html/tai-lieu-hoc-html
		https://webcoban.vn/html/phan-tu-khoi-va-phan-tu-noi-tuyen-trong-html.html

	Javascript:
		(30 bài) : https://toidicode.com/javascript-la-gi-viet-chuong-trinh-dau-tien-39.html
		https://hocjavascript.net/tong-quan/tac-dung-cua-console-trong-viec-debug/

		đồng hồ kim : https://devforum.info/dong-ho-kim-bang-javascript-b180.html
		Cờ Caro :     
			https://game-caro-js-two.vercel.app/
			https://techmaster.vn/posts/37756/huong-dan-tao-game-co-caro-bang-javascript


	CSS:
		https://toidicode.com/css-la-gi-34.html
		https://toidicode.com/selectors-trong-css-153.html

	DOM: Document Object Model
		https://toidicode.com/dom-elements-trong-javascript-112.html
		https://topdev.vn/blog/dom-la-gi/

	Selector CSS:
		https://www.daipho.com/blog/bang-doi-chieu-cac-css-selector/

	MYSQL:
		https://www.thegioididong.com/game-app/huong-dan-cach-tai-cai-dat-mysql-ban-moi-nhat-chi-tiet-tung-1299084

		Cài MySQL Server 8.2
		https://openplanning.net/10237/huong-dan-hoc-sql-cho-nguoi-moi-bat-dau-voi-mysql
			
			Root password: Dhg2974@
			Window Server Name: MySQL82
			Dir: C:\ProgramData\MySQL\MySQL Server 8.2\Data

		Cài MySQL WorkBench
			https://dev.mysql.com/downloads/workbench/

		Các lệnh cơ bản:
			https://viblo.asia/p/mot-so-cau-lenh-cmd-huu-ich-khi-su-dung-mysql-gioi-thieu-mot-so-kieu-storage-engine-trong-mysql-RQqKLbOMl7z

		Đăng nhập MySQL server:
			C:\Users\HP>cd\
			C:\>cd C:\Program Files\MySQL\MySQL Server 8.2\bin
			C:\Program Files\MySQL\MySQL Server 8.2\bin>mysql -u root -p
			Enter the password: Dhg2974@

		Tạo user quang với pwd là 361133059: 
			mysql > CREATE USER 'quang' IDENTIFIED BY '361133059'; 
			Query OK, 0 rows affected (0.03 sec)
			mysql >

		Xóa user quang: 
			mysql > DROP USER 'quang'; 
			Query OK, 0 rows affected (0.03 sec)
			mysql >

		Cấp quyền SELECT:
			mysql > GRANT SELECT ON *.* TO 'quang';

		Cấp quyền TOÀN BỘ:
			mysql > GRANT ALL PRIVILEGES ON *.* TO 'quang';
			Query OK, 0 rows affected (0.02 sec)
			mysql >

		Tạo Database mysql_quang:
			mysql> create database mysql_quang;
			Query OK, 1 row affected (0.02 sec)
			mysql>

		Xóa Database mysql_quang:
			mysql> drop database mysql_quang;
			Query OK, 1 row affected (0.02 sec)
			mysql>

		Tạo Database quang_mydb:
			mysql> create database quang_mydb;
			Query OK, 1 row affected (0.02 sec)
			mysql>
		
	XAMPP:
		https://toidicode.com/huong-dan-cai-dat-xampp-52.html

	URL:
		href: http://toidicode.com/?a=5
		auth: null
		hash: null
		host: toidicode.com
		hostname: toidicode.com
		path: /?a=5
		pathname: /
		port: null
		protocol: http:
		query: 5
		search: ?a=5
		slashes: true

	Node js:
		https://toidicode.com
		https://toidicode.com/nodejs-co-ban?page=1
		https://toidicode.com/nodejs-co-ban?page=2
		https://toidicode.com/series/nodejs-co-ban

	app android by nodejs
		https://itzone.com.vn/vi/article/huong-dan-tao-1-ung-dung-android-bang-flutter-nodejs-phan-1/

	anroid studio
		https://xuanthulab.net/tim-hieu-ve-activity-va-vong-doi-activity.html

	flutter
		https://viblo.asia/p/hoc-flutter-tu-co-ban-den-nang-cao-phan-1-lam-quen-co-nang-flutter-4dbZNJOvZYM
		
		https://viblo.asia/p/hoc-flutter-tu-co-ban-den-nang-cao-phan-2-statefulwidget-vs-statelesswidget-khi-nao-thi-can-su-dung-cai-nao-ORNZq12rZ0n
		
		https://viblo.asia/p/hoc-flutter-tu-co-ban-den-nang-cao-phan-3-lot-tran-co-nang-flutter-buildcontext-la-gi-bWrZnmdbKxw

		https://viblo.asia/p/hoc-flutter-tu-co-ban-den-nang-cao-phan-4-lot-tran-inheritedwidget-3P0lPDbmlox

		https://viblo.asia/p/hoc-flutter-tu-co-ban-den-nang-cao-phan-5-co-nang-flutter-hoat-dong-nhu-the-nao-3Q75w1G7ZWb

		https://viblo.asia/p/hoc-flutter-tu-co-ban-den-nang-cao-phan-6-key-la-gi-co-mo-khoa-trai-tim-nang-duoc-khong-ORNZqk4q50n

		https://viblo.asia/p/hoc-flutter-tu-co-ban-den-nang-cao-phan-7-lot-tran-trui-globalkey-bJzKmPxk59N

		https://viblo.asia/p/hoc-flutter-phan-1-tao-ung-dung-dau-tien-hello-world-RnB5pMADKPG#_1-set-up-moi-truong-2

		https://viblo.asia/p/flutter-5-ly-do-vi-sao-ban-muon-hoc-no-gDVK2n2nKLj


	uploaf file in node js use module multiparty :
		https://stackoverflow.com/questions/46107236/error-on-node-js-file-to-upload
	
	CSS:
		https://quantrimang.com/hoc/hoc-css

	Node.js (search google: Node.js Tutorial: Phần ?)
		https://viblo.asia/p/nodejs-tutorial-phan-1-gioi-thieu-va-cai-dat-ung-dung-dau-tien-gVQvlwdykZJ
		https://viblo.asia/p/nodejs-tutorial-phan-2-module-trong-nodejs-MgNvWDdKGYxhttps://viblo.asia/p/https://viblo.asia/p/nodejs-tutorial-phan-3-promise-trong-nodejs-eoazLJnEROm
		https://viblo.asia/p/nodejs-tutorial-phan-4-express-framework-924lJXpNKPM
		https://viblo.asia/p/nodejs-tutorial-phan-5-express-route-GrLZD94elk0


	Python:	
	https://toidicode.com/python-co-ban
	https://viettuts.vn/bai-tap-python
	https://github.com/thantrieu/Python-Tutorial/blob/master/OpenCV%20tutorial/video_stream.py
	https://www.youtube.com/watch?v=5Pb9tl41Hz4
	https://codelearn.io/sharing/xu-ly-du-lieu-voi-pandas-trong-python
	https://bootstrap.pypa.io/pip/2.7/get-pip.py
	https://viblo.asia/p/dieu-khien-ban-phim-voi-pynput-Ljy5VzO35ra
	https://developers.google.com/edu/python/strings
	https://www.lfd.uci.edu/~gohlke/pythonlibs/             (google search: windows python lxml)

	VBnet cơ bản
	https://freetuts.net/toan-tu-trong-visual-basic-3107.html
	https://timoday.edu.vn/wp-content/uploads/2017/03/Ch5_LapTrinhHuongDoiTuong.pdf
	
	vbnet nâng cao
	https://sites.google.com/site/vodailuong/tap-huan-lap-trinh/visual-basic-net

	Luồng
	https://tuhocict.com/huong-dan-tu-hoc-lap-trinh-socket-tcp-ip/
	https://tuhocict.com/ung-dung-mang-mang-may-tinh-giao-thuc/
	https://tuhocict.com/thread-multi-threading-lap-trinh-da-luong/

	https://codelearn.io/sharing/thread-va-tasks-trong-csharp
	https://xuanthulab.net/lap-trinh-bat-dong-bo-asynchronou-c-c-sharp-voi-bat-dong-bo-theo-mo-hinh-tac-vu.html

	C# cơ bản
	https://howkteam.vn/course/khoa-hoc-lap-trinh-c-can-ban/c-la-gi-13

	C# hướng đối tượng
	https://howkteam.vn/Course/Lap-trinh-OOP-voi-C/Class-trong-Lap-trinh-huong-doi-tuong-1370
	
	C# nâng cao
	https://howkteam.vn/course/khoa-hoc-lap-trinh-c-nang-cao-39

	json
	https://tuhocict.com/cai-tien-view-1-nuget-newtonsoft-json/

	asp net
	https://tedu.com.vn/series/hoc-aspnet-core-can-ban.html

	WPF C#
	https://howkteam.vn/course/lap-trinh-wpf-co-ban-30

	Window form cơ bản C#
	https://howkteam.vn/course/lap-trinh-winform-co-ban-27

	Công cụ tester tự động
	https://codelearn.io/sharing/lap-trinh-cong-cu-tu-dong-phan-1

	Selenium
	https://howkteam.vn/course/khoa-hoc-selenium-co-ban-den-nang-cao-40

	'Transaction
	https://viblo.asia/p/tim-hieu-sql-transaction-va-cach-su-dung-trong-laravel-yMnKMnLzZ7P
	https://maithehungit.wordpress.com/2013/06/04/note-1/
	https://www.ddth.com/showthread.php/381292-C%E1%BA%A7n-ai-hi%E1%BB%83u-s%C3%A2u-v%E1%BB%81-SQL-Server-gi%C3%BAp-%C4%91%E1%BB%A1-t%C3%ACm-nguy%C3%AAn-nh%C3%A2n-SQL-ch%E1%BA%ADm

	'SQL
	https://howkteam.vn/course/su-dung-sql-server/gioi-thieu-sql-va-sql-server-1362

	'Data Type SQL
	https://www.sqlservertutorial.net/sql-server-basics/sql-server-data-types/

	'Tối ưu SQL 
	Phần 1:  https://code4shares.wordpress.com/2016/09/16/toi-uu-hieu-nang-sql-phan-1-datetime/
	Phần 2:  https://code4shares.wordpress.com/2016/09/18/toi-uu-hieu-nang-sql-phan-2-delete/
	Phần 3:  https://code4shares.wordpress.com/2016/10/30/toi-uu-hieu-nang-sql-phan-3-exists-in-va-nguoi-thu-ba/
	Phần 4:  https://code4shares.wordpress.com/2016/12/04/toi-uu-hieu-nang-sql-phan-4-trigger/
	Phần 5:  https://code4shares.wordpress.com/2017/01/10/toi-uu-hieu-nang-sql-phan-5-random/
	Phần 6:  https://code4shares.wordpress.com/2017/02/15/toi-uu-hieu-nang-sql-phan-update-hay-merge/
	Phần 7:  https://code4shares.wordpress.com/2017/04/28/toi-uu-sql-phan-7-chuyen-ngan-cua-id/
	Phần 8:  https://code4shares.wordpress.com/2017/06/04/toi-uu-sql-phan-8-1-cau-chuyen-don-gian-ve-viec-cong-chuoi/
	Phần 9:  https://code4shares.wordpress.com/2017/07/18/toi-uu-sql-phan-9-tinh-tong-cac-dong/
	phần 10: https://code4shares.wordpress.com/2017/08/10/toi-uu-sql-phan-10-lai-la-cau-chuyen-ve-guid-id/
	https://code4shares.wordpress.com/2016/08/26/bong-tuyet-co-doc/

	'CTE Common Table Expression
	https://data-fun.com/mysql-common-table-expression-with/

	'CROSS APPLY
	https://laptrinhvb.net/bai-viet/co-so-du-lieu/--DATABASE---Huong-dan-su-dung-CROSS-APPLY-va-OUTER-APPLY-trong-sqlserver/af4a03924a465247.html
		-> liên kết với BẢNG thì dùng JOIN (ví dụ CROSS JOIN)
		-> liên kết với HÀM thì dùng APPLY (ví dụ CROSS APLLY)

	'FOR XML PATH('')

		CREATE TABLE #YourTable ([ID] INT, [Name] CHAR(1), [Value] INT)
 
		INSERT INTO #YourTable ([ID],[Name],[Value]) VALUES (1,'A',4)
		INSERT INTO #YourTable ([ID],[Name],[Value]) VALUES (1,'B',8)
		INSERT INTO #YourTable ([ID],[Name],[Value]) VALUES (2,'C',9)
		INSERT INTO #YourTable ([ID],[Name],[Value]) VALUES (2,'D',10)
		 
		SELECT 
		  [ID],
		  STUFF(
			(
		    SELECT '|' + [Name] 
		    FROM #YourTable 
		    WHERE (ID = Results.ID) 
			FOR XML PATH('')
			)
		  ,1,1,'') 
		  AS NameValues
		FROM #YourTable Results
		GROUP BY ID

	'Difference between Table and View
	https://www.javatpoint.com/table-vs-view#:~:text=A%20table%20consists%20of%20rows%20and%20columns%20to%20store%20and,table%20extracted%20from%20a%20database.
	
	'CTE and Temp Table difference
	https://www.google.com/search?q=cte+and+temp+table+difference&hl=vi&sxsrf=APwXEdeJu-ifsKpGmWTDPxieCFZEVQH4JQ%3A1683515890583&ei=8mlYZP2eI4WQhwOK6IT4DA&oq=CTE+and+table+%24&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQARgBMgYIABAWEB4yBggAEBYQHjIGCAAQFhAeMgYIABAWEB4yBggAEBYQHjIICAAQFhAeEAoyBggAEBYQHjIICAAQFhAeEAoyBggAEBYQHjIICAAQFhAeEAo6BwgjEOoCECc6BwgjEIoFECc6BAgjECc6BwgAEIoFEEM6CAgAEIAEELEDOgsIABCKBRCxAxCDAToFCAAQgAQ6CwguEIMBELEDEIAEOhEILhCABBCxAxCDARDHARCvAToLCAAQgAQQsQMQgwE6CwguEIAEEMcBEK8BOgoIABCKBRCxAxBDOgkIABCKBRAKEEM6BQguEIAEOhMILhCABBCXBRDcBBDeBBDgBBgBOgUIIRCgAToHCAAQExCABDoICAAQFhAeEBM6CggAEBYQHhATEAo6CQgAEA0QExCABEoECEEYAFAAWMKBAWCQpwFoBnABeAGAAasBiAH8EZIBBDAuMTmYAQCgAQGwAQrAAQHaAQYIARABGBQ&sclient=gws-wiz-serp

	'Các Store procedure hệ thống mà developer phải biết
	http://bis.net.vn/forums/t/81.aspx
	https://laptrinhvb.net/bai-viet/co-so-du-lieu/--SQL-SERVER---TOP-50-CAU-LENH-SQLSERVER-QUAN-TR0NG-NEN-BIET-(PHAN-1)/33d2d15d8a3cd32f.html

		1/ Xem toàn bộ các database đang có
				sp_helpdb 
		2/ Xem nội dung store procedure
				sp_helptext 'PKT_GTSX2017' 
				
				encryp store or function
				https://dba.stackexchange.com/questions/60129/how-to-view-an-encrypted-view-or-stored-procedure

		3/ Xem tất cả các store procedure
				select * from sys.objects where [type]='P' order by [Name] 
		4/ Xem kích thước tất cả table
				SELECT sob.name AS Table_Name,SUM(sys.length) AS [Size_Table(Bytes)]  
				FROM sysobjects sob, syscolumns sys  
				WHERE sob.xtype='u' AND sys.id=sob.id  
				GROUP BY sob.name
		5/ Liệt kê tất cả các bảng Table mà không có sử dụng Indetity (AutoNumber)
				SELECT TABLE_NAME FROM INFORMATION_SCHEMA.TABLES  
				WHERE Table_NAME NOT IN (
						SELECT DISTINCT c.TABLE_NAME FROM INFORMATION_SCHEMA.COLUMNS c  
						INNER JOIN sys.identity_columns ic  
							on (c.COLUMN_NAME=ic.NAME)
						) 
					  AND TABLE_TYPE ='BASE TABLE'
		6/ Tìm kiếm danh sách tất cả các khóa chính và khóa ngoại trong cơ sở dữ liệu
				select * from INFORMATION_SCHEMA.KEY_COLUMN_USAGE	
		7/ Liệt số số lượng tất cả các Record của những table trong Database
				CREATE TABLE #Tab  
				(  
				Table_Name [varchar](max),  
				Total_Records int  
				);  
				EXEC sp_MSForEachTable @command1=' Insert Into #Tab(Table_Name, Total_Records) SELECT ''?'', COUNT(*) FROM ?'  
				SELECT * FROM #Tab t ORDER BY t.Total_Records DESC;  
				DROP TABLE #Tab; 
		8/ Version SQL, ngôn ngữ trong SQL, số lẻ thập phân, session_ID hiện hành của User
				select @@VERSION, @@LANGUAGE, @@MAX_PRECISION, @@SPID
		9/ Liệt kê tất cả danh sách Store Procedure được chỉnh sửa (thay đổi) theo số ngày quy định (10 ngày)
				SELECT name,a.modify_date  
				FROM sys.objects a
				WHERE type='P' AND DATEDIFF(D,modify_date,GETDATE())< 10
				order by a.modify_date desc
		10/ Liệt kê tất cả danh sách Store Procedure được tạo mới theo số ngày quy định (10 ngày)
				SELECT name,a.create_date  
				FROM sys.objects a
				WHERE type='P' AND DATEDIFF(D,create_date,GETDATE())< 10
				order by a.create_date desc
		11/ Biên dịch lại một hàm Store Procedure
				EXEC sp_recompile'Procedure_Name'
		12/ Biên dịch lại tất cả các Store Procedure trong một bảng table
				EXEC sp_recompile N'Table_Name'
		13/ Liệt kê tất cả bảng dữ liệu chưa có cài đặt khóa chính (Primary Key)
				SELECT name AS Table_Name  
				FROM sys.tables  
				WHERE OBJECTPROPERTY(OBJECT_ID,'TableHasPrimaryKey') = 0  
				ORDER BY Table_Name;

		14/ Thêm cột include vào noncluster index đã có:
			CREATE INDEX IX_NC_TableName_ColumnName
			ON TableName(ColumnName)
			INCLUDE(Col1, Col2, Col3, Col4)
			WITH(DROP_EXISTING = ON);

		15/ Xem các field index và include trong noncluster-index của user table
			SELECT --a.column_id,a.is_included_column,a.index_id,a.object_id as table_id,
				d.Name as Table_Name,b.name as Index_Name
				,case when a.is_included_column=0 then c.name else '' end	
					as Column_Name_Index
				,case when a.is_included_column=1 then c.name else '' end	
					as Column_Name_Include
			FROM sys.index_columns a
			inner join sys.indexes b on b.index_id=a.index_id
			inner join sys.all_columns c on c.object_id=a.object_id and c.column_id=a.column_id
			inner join sys.tables d on d.object_id=a.object_id
			where d.name='eMobiz_ARDoc' and b.name='idx_LastUpdatedDateTime' 

		15.1/ Xem các field index của Table Valued Function (SplitRange) TVF
			--select a.Name as index_Name,d.name as table_Name ,c.name as column_Name
			--from sys.indexes a
			--inner join sys.index_columns b on b.object_id=a.object_id and --b.index_column_id=a.index_id
			--inner join sys.all_columns c on c.object_id=a.object_id and --c.column_id=a.index_id
			--inner join sys.objects d on d.object_id=a.object_id
			--where a.Name='PK__SplitRange__6C98FCFF' 

			select a.Name as index_Name,d.name as table_Name ,c.name as column_Name
			from sys.indexes a
			inner join sys.index_columns b on b.object_id=a.object_id and b.index_id=a.index_id
			inner join sys.all_columns c on c.object_id=a.object_id and c.column_id=b.column_id
			inner join sys.objects d on d.object_id=a.object_id
			where a.Name='PK__SplitRan__75FE9D98DC9B4661' 
			--where a.Name='IX_SplitRange_LoValue' 

		15.2/ Chú ý phân biệt TVF và iTVF
			SplitRange là TVF : Table Valued Function (có khai biến bảng @XYZ trong hàm)
				https://www.geeksforgeeks.org/multi-statement-table-valued-function-in-sql-server/
			Hàm SplitRange có khai báo bảng với cột position là primary key

			SplitString là iTVF : InLine Table Valued Function (không có khai biến bảng trong hàm, chỉ cần khai báo là RETURN TABLE)
				https://www.geeksforgeeks.org/inline-table-valued-function-in-sql-server/

		16/ Execution Plan in SQL:  
			https://www.sqlshack.com/execution-plans-in-sql-server/
			
			https://www.sqlshack.com/sql-server-execution-plan-operators-part-1/

			https://www.sqlshack.com/sql-server-execution-plan-operators-part-2/

			https://www.sqlshack.com/sql-server-execution-plan-operators-part-3/

			https://www.sqlshack.com/sql-server-execution-plan-operators-part-3/#:%7E:text=SQL%20Server%20Compute%20Scalar%20operator%20is%20used%20to%20calculate%20a,concatenation%20of%20the%20scalar%20value.

			https://learn.microsoft.com/en-us/answers/questions/160062/execution-plan-compute-scala

			SET SHOWPLAN_TEXT ON  
			https://learn.microsoft.com/en-us/sql/t-sql/statements/set-showplan-text-transact-sql?view=sql-server-ver16

			https://learn.microsoft.com/en-us/sql/relational-databases/showplan-logical-and-physical-operators-reference?view=sql-server-ver16

			https://learn.microsoft.com/en-us/sql/relational-databases/performance/joins?view=sql-server-ver16#nested_loops

			Hash Table
			https://blog.luyencode.net/bang-bam-hash-tables/
			select (97*1 + 98*2 + 99*3 + 100*4 + 101*5 + 102*6) % 2069 --  2107 % 2069 = 38
			select (98*1 + 99*2 + 100*3 + 101*4 + 102*5 + 97*6) % 2069 --  2092 % 2069 = 23
			select (99*1 + 100*2 + 101*3 + 102*4 + 97*5 + 98*6) % 2069 --  2083 % 2069 = 14
			select (100*1 + 101*2 + 102*3 + 97*4 + 98*5 + 99*6) % 2069 --  2080 % 2069 = 11

			Băm 1 cặp số nguyên bằng hàm Cantor hoặc Szudzik
			https://sair.synerise.com/efficient-integer-pairs-hashing/
			F:\My Drive\NhaTro_MaiHoa\Hash_Cantor_Function.xlsx

			https://math.stackexchange.com/questions/882877/produce-unique-number-given-two-integers

			https://stackoverflow.com/questions/30734848/order-independent-hash-algorithm

			https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/practice-problems/algorithm/valid-pairs-4f78e507/

			bài toán cái túi (quy hoạch động : dynamic-programming)
			https://viblo.asia/p/phan-2thuat-toan-quy-hoach-dong-maGK73zbKj2
			https://viblo.asia/p/phan-1thuat-toan-quy-hoach-dong-QpmleJzM5rd
			https://www.geeksforgeeks.org/0-1-knapsack-problem-dp-10/

			https://www.geeksforgeeks.org/dynamic-programming/
			https://www.geeksforgeeks.org/0-1-knapsack-problem-dp-10/

			Bitmap 
			https://www.sql.kiwi/2011/07/bitmap-magic.html

		17/ Computed field in SQL
			CREATE TABLE [dbo].[Employee_test]
			([EmpID]   [INT] NOT NULL, 
			 [EmpName] [VARCHAR](50) NOT NULL, 
			 [DOB]     [DATE] NOT NULL, 
			 [Age] AS (DATEDIFF(yy, [DOB], GETDATE())), 
			 CONSTRAINT [PK_Employee_test] PRIMARY KEY CLUSTERED([EmpID] ASC)
			);

			Insert into [Employee_test] (EmpID,EmpName,DOB) values(1,'Raj','1987-01-01')
			Insert into [Employee_test] (EmpID,EmpName,DOB) values(2,'Mohan','1985-06-07')
			Insert into [Employee_test] (EmpID,EmpName,DOB) values(3,'Ram','1983-09-01')

			select * from [Employee_test]
			ALTER TABLE [Employee_test]
			ADD [RetirementDate] AS (DATEADD(year,60, [DOB]));

			update [Employee_test] set DOB='1967-12-17' where EmpID=1
			select * from [Employee_test]

		18/ Xem tất cả các cột computed trong database
			SELECT SCHEMA_NAME(o.schema_id) AS schema_name, 
			    c.name AS column_name, 
			    OBJECT_NAME(c.object_id) AS table_name, 
			    TYPE_NAME(user_type_id) AS data_type, 
			    definition
			FROM sys.computed_columns c
			  JOIN sys.objects o ON o.object_id = c.object_id
			ORDER BY schema_name, table_name, column_id

		19/how-to-find-out-the-dependencies-of-stored-procedure-using-sql
		
		https://stackoverflow.com/questions/52070058/how-to-find-out-the-dependencies-of-stored-procedure-using-sql

		20/SELECT *
			https://www.sqlshack.com/design-sql-queries-better-performance-select-exists-vs-vs-joins/

			INLINE FUNCTION	
			https://www.geeksforgeeks.org/inline-table-valued-function-in-sql-server/

			chú ý đặc biệt: tuyệt đối tránh 
				phép toán WHERE .... IN (select ....) -> chạy rất chậm 
			ví dụ: trong 3 query sau, query 1 và 2 speed=0% trong khi query3 speed=100%
				query1:
					select * from Item  
					where No_ in ('4HTL01','4HTL02','4HTL03')

				quer2:
					select a.* from Item a 
						inner join (
								select '4HTL01' as ms union all 
								select '4HTL02' as ms union all 
								select '4HTL03' as ms
							) b
								on b.ms=a.No_

				query3:
					select * from Item 
					where No_ in (
						select '4HTL01' as ms union all 
						select '4HTL02' as ms union all 
						select '4HTL03' as ms)

		21/ SET STATISTICS IO ON

			SCAN COUNT , LOGICAL READ
			https://dba.stackexchange.com/questions/316824/what-is-the-meaning-of-scan-count-in-set-statistics-io-on

			https://learn.microsoft.com/en-us/archive/blogs/sqlserverfaq/scan-count-meaning-in-set-statistics-io-output

			https://learn.microsoft.com/en-us/archive/blogs/sqlserverfaq/scan-count-meaning-in-set-statistics-io-output-part-2


		22/ WHAT IS WORKTABLE
		https://blog.sqlauthority.com/2017/11/05/worktable-sql-server-interview-question-week-146/

		23/ WHAT IS WORKFILE

		25/ How To Find Missing Indexes
		https://sqlnuggets.com/sql-scripts-how-to-find-missing-indexes/#:~:text=What%20Are%20Missing%20Indexes%3F,to%20them%2C%20Missing%20Index%20Suggestions.
		
		SELECT db.[name] AS [DatabaseName]
		    ,id.[object_id] AS [ObjectID]
			,OBJECT_NAME(id.[object_id], db.[database_id]) AS [ObjectName]
		    ,id.[statement] AS [FullyQualifiedObjectName]
		    ,id.[equality_columns] AS [EqualityColumns]
		    ,id.[inequality_columns] AS [InEqualityColumns]
		    ,id.[included_columns] AS [IncludedColumns]
		    ,gs.[unique_compiles] AS [UniqueCompiles]
		    ,gs.[user_seeks] AS [UserSeeks]
		    ,gs.[user_scans] AS [UserScans]
		    ,gs.[last_user_seek] AS [LastUserSeekTime]
		    ,gs.[last_user_scan] AS [LastUserScanTime]
		    ,gs.[avg_total_user_cost] AS [AvgTotalUserCost]  -- Average cost of the user queries that could be reduced by the index in the group.
		    ,gs.[avg_user_impact] AS [AvgUserImpact]  -- The value means that the query cost would on average drop by this percentage if this missing index group was implemented.
		    ,gs.[system_seeks] AS [SystemSeeks]
		    ,gs.[system_scans] AS [SystemScans]
		    ,gs.[last_system_seek] AS [LastSystemSeekTime]
		    ,gs.[last_system_scan] AS [LastSystemScanTime]
		    ,gs.[avg_total_system_cost] AS [AvgTotalSystemCost]
		    ,gs.[avg_system_impact] AS [AvgSystemImpact]  -- Average percentage benefit that system queries could experience if this missing index group was implemented.
		    ,gs.[user_seeks] * gs.[avg_total_user_cost] * (gs.[avg_user_impact] * 0.01) AS [IndexAdvantage]
		    ,'CREATE INDEX [IX_' + OBJECT_NAME(id.[object_id], db.[database_id]) + '_' + REPLACE(REPLACE(REPLACE(ISNULL(id.[equality_columns], ''), ', ', '_'), '[', ''), ']', '') + CASE
		        WHEN id.[equality_columns] IS NOT NULL
		            AND id.[inequality_columns] IS NOT NULL
		            THEN '_'
		        ELSE ''
		        END + REPLACE(REPLACE(REPLACE(ISNULL(id.[inequality_columns], ''), ', ', '_'), '[', ''), ']', '') + '_' + LEFT(CAST(NEWID() AS [nvarchar](64)), 5) + ']' + ' ON ' + id.[statement] + ' (' + ISNULL(id.[equality_columns], '') + CASE
		        WHEN id.[equality_columns] IS NOT NULL
		            AND id.[inequality_columns] IS NOT NULL
		            THEN ','
		        ELSE ''
		        END + ISNULL(id.[inequality_columns], '') + ')' + ISNULL(' INCLUDE (' + id.[included_columns] + ')', '') AS [ProposedIndex]
		    ,CAST(CURRENT_TIMESTAMP AS [smalldatetime]) AS [CollectionDate]
		FROM [sys].[dm_db_missing_index_group_stats] gs WITH (NOLOCK)
		INNER JOIN [sys].[dm_db_missing_index_groups] ig WITH (NOLOCK) ON gs.[group_handle] = ig.[index_group_handle]
		INNER JOIN [sys].[dm_db_missing_index_details] id WITH (NOLOCK) ON ig.[index_handle] = id.[index_handle]
		INNER JOIN [sys].[databases] db WITH (NOLOCK) ON db.[database_id] = id.[database_id]
		WHERE  db.[database_id] = DB_ID()
		--AND OBJECT_NAME(id.[object_id], db.[database_id]) = 'YourTableName'
		ORDER BY ObjectName, [IndexAdvantage] DESC
		OPTION (RECOMPILE);

		26/ Encrypted store, function, ... and other object in sql
			
			https://dba.stackexchange.com/questions/60129/how-to-view-an-encrypted-view-or-stored-procedure

			https://sqlity.net/en/1617/decrypting-encrypted-database-objects/

		27/ SET ANSI_NULLS : The default for SET ANSI_NULLS is OFF.
			https://learn.microsoft.com/en-us/sql/t-sql/statements/set-ansi-nulls-transact-sql?view=sql-server-ver16

		28/ SET QUOTED_IDENTIFIER: The default for SET QUOTED_IDENTIFIER is ON.
			https://learn.microsoft.com/en-us/sql/t-sql/statements/set-quoted-identifier-transact-sql?view=sql-server-ver16

		29/ SQL SERVER NON-Clustered Index on table variable?
			https://stackoverflow.com/questions/4645210/sql-server-non-clustered-index-on-table-variable

			Starting SQL Server 2014, you can create nonclustered index inline while declaring the table variable.

			DECLARE @TabVar TABLE 
			(
			    ID INT PRIMARY KEY, 
			    FNAME NVARCHAR(100) INDEX IX2 NONCLUSTERED
			)

			declare @Stock table
		    (
		        StockId     int     NOT NULL
		    ,   FieldId     int     NOT NULL
		    ,   StockDate   date    NOT NULL
		    ,   StockValue  float   NULL
		    ,   INDEX IX_Priyanka NONCLUSTERED(StockId, FieldId, StockDate desc) 
		    )  

		    DECLARE @MyTable TABLE (
		    	IXField1 int, IXFiled2 int, Field3 bit, 
		    	HelperIX int IDENTITY (1,1), 
		    	PRIMARY KEY/UNIQUE (IXField1, IXField2, HelperIX)
		    	)

		   30/ IDENTITY(1,1) NOT FOR REPLICATION NOT NULL
			   	CREATE TABLE [dbo].[Table_1]
				(
					[ProductID] [int] IDENTITY(1,1) NOT FOR REPLICATION PRIMARY KEY ,
					[ProductName] [varchar](50) NULL,
					[ProductDescription] [varchar](100) NULL
				) 

				https://www.mssqltips.com/sqlservertip/1274/change-not-for-replication-value-for-sql-server-identity-columns/#:~:text=The%20%22Not%20For%20Replication%22%20setting,subscriber%20creating%20a%20new%20ID.

				https://dba.stackexchange.com/questions/36478/primary-key-with-not-for-replication-option

				Example about Replication
				https://repltalk.com/2010/02/22/all-about-not-for-replication/

				https://learn.microsoft.com/en-us/previous-versions/sql/sql-server-2008-r2/ms152529(v=sql.105)?redirectedfrom=MSDN

				Replication Merge Agent

				https://learn.microsoft.com/en-us/sql/relational-databases/replication/agents/replication-merge-agent?view=sql-server-ver16

	'Cách lấy 1 hoặc nhiều data set trả về từ 1 store
	https://learn.microsoft.com/en-us/answers/questions/746132/how-can-we-get-the-full-output-of-sp-help-system-s
	Example:
		CREATE Procedure TestingMultipleSET AS
		    SELECT 'Set 1' as MySet, 'TestingMultipleSET1' as txt  
		    SELECT 'Set 2' as MySet, 'TestingMultipleSET2' as txt 

		IF OBJECT_ID('TempDB..#MyTable','U') IS NOT NULL
			DROP TABLE #MyTable
		CREATE TABLE #MyTable(MySet varchar(5),txt varchar(19));
		INSERT #MyTable EXECUTE TestingMultipleSET;
		SELECT * FROM #MyTable

		'Tạo bảng động
		DECLARE @sqlCommand NVARCHAR(MAX)
	    select @sqlCommand = 'CREATE TABLE #MyTable(' + STRING_AGG ([name] + ' ' +  system_type_name, ',') + ');'
		from sys.dm_exec_describe_first_result_set ('EXEC TestingMultipleSET', null,0)
	    PRINT @sqlCommand
	    EXECUTE sp_executesql @sqlCommand

	'kỹ thuật sử dụng bảng tạm # và ##:
		Bảng tạm # dùng khi select trực tiếp hoặc gián tiếp và chỉ có hiệu lực trong phiên làm việc hiện hành. Ví dụ:
			IF OBJECT_ID('TempDB..#tmp','U') IS NOT NULL
  				DROP TABLE #tmp
			select a.* into #tmp from (select 'a' as F1 union select 'b' as F1) a
			select * from #tmp
			declare @sql nvarchar(max)='select * from #tmp'
			execute (@sql)

			Mở phiên làm việc mới (new query): 
				chạy select * from #tmp sẽ thấy báo lỗi không tìm thấy #tmp
					(Invalid object name '#tmp')

		Bảng tạm ## giống hệt # chỉ khác là có hiệu lực ở tất cả các phiên làm việc. Ví dụ:
			IF OBJECT_ID('TempDB..##tmp','U') IS NOT NULL
  				DROP TABLE ##tmp
			select a.* into ##tmp from (select 'a' as F1 union select 'b' as F1) a
			select * from ##tmp
			declare @sql nvarchar(max)='select * from ##tmp'
			execute (@sql)

			Mở phiên làm việc mới (new query): 
				chạy select * from ##tmp sẽ trả về kết quả bình thường như phiên trước

		Ứng dụng:
		1/ Tạo bảng tạm bên ngoài để sử dụng trong chuỗi thì dùng # hay ## đều được.
			Ví dụ: cả 2 script sau đểu trả về kết quả tốt
			script 1:
				IF OBJECT_ID('TempDB..#tmp','U') IS NOT NULL
				  	DROP TABLE #tmp
				select a.* into #tmp from (select 'a' as F1 union select 'b' as F1) a
				select * from #tmp
				declare @sql nvarchar(max)='select * from #tmp'
				execute (@sql)

			script 2:
				IF OBJECT_ID('TempDB..##tmp','U') IS NOT NULL
				  	DROP TABLE ##tmp
				select a.* into ##tmp from (select 'a' as F1 union select 'b' as F1) a
				select * from ##tmp
				declare @sql nvarchar(max)='select * from ##tmp'
				execute (@sql)

		2/ Nhưng ngược lại, tạo bảng tạm trong chuỗi để ra ngoài sử dụng thì bắt buộc phải dùng ##
			Ví dụ: trong 2 script sau, script 1 báo lỗi nhưng script 2 chạy tốt
			script 1:
				IF OBJECT_ID('TempDB..#tmp2','U') IS NOT NULL
				  	DROP TABLE #tmp2
				declare @sql nvarchar(max)='select a.* into #tmp2 from (select ''a'' as F1 											union select ''b'' as F1) a'
				execute (@sql)
				select * from #tmp2

			script 2:
				IF OBJECT_ID('TempDB..##tmp2','U') IS NOT NULL
				  	DROP TABLE ##tmp2
				declare @sql nvarchar(max)='select a.* into ##tmp2 from (select ''a'' as F1 											union select ''b'' as F1) a'
				execute (@sql)
				select * from ##tmp2


	'Tập view hệ thống của SQL mà coder cần biết
	sys.dm_exec.......


	'cách lấy thông tin column của 1 table
	Create Procedure SCHEMA_INFO (@tblname varchar(255))

	as

	Begin

	/*

	Ref: Task [#821]

	Name: identify_table_info.sql

	Version: 1.0

	Author: Glen Wass

	Date Created: 19/10/2011

	Description: script to display a table design

	Impact:

	Example exec: exec SCHEMA_INFO 'country'

	Version History: DateVersionAuthorComments

	---------------------------------------------------------------------------

	19/10/2011|1.0| GW | Initial release

	*/ 

	-- find object id

	declare @objid int,

	@precscaletypes nvarchar(150) 

	select @objid=object_id from sys.all_objects where object_id = object_id(@tblname)

	select @precscaletypes = N'tinyint,smallint,decimal,int,bigint,real,money,float,numeric,smallmoney,date,time,datetime2,datetimeoffset,' 

	 ----reurn all collumns and respective data properties

	 select

	 'Column_name' = name,

	 'Type' = type_name(user_type_id),

	 'Computed' = case when ColumnProperty(object_id, name, 'IsComputed') = 0 then 'no' else 'yes' end,

	 'Length' = convert(int, max_length),

	 -- for prec/scale, only show for those types that have valid precision/scale

	 -- Search for type name + ',', because 'datetime' is actually a substring of 'datetime2' and 'datetimeoffset'

	 'Prec' = case when charindex(type_name(system_type_id) + ',', @precscaletypes) > 0

	 then convert(char(5),ColumnProperty(object_id, name, 'precision'))

	 else ' ' end,

	 'Scale' = case when charindex(type_name(system_type_id) + ',', @precscaletypes) > 0

	 then convert(char(5),OdbcScale(system_type_id,scale))

	 else ' ' end,

	 'Nullable' = case when is_nullable = 0 then 'no' else 'yes' end,

	 'TrimTrailingBlanks' = case ColumnProperty(object_id, name, 'UsesAnsiTrim')

	 when 1 then 'no'

	 when 0 then 'yes'

	 else '(n/a)' end,

	 'FixedLenNullInSource' = case

	 when type_name(system_type_id) not in ('varbinary','varchar','binary','char')

	 then '(n/a)'

	 when is_nullable = 0 then 'no' else 'yes' end,

	 'Collation' = collation_name

	 from sys.all_columns where object_id = @objid

	End

	exec SCHEMA_INFO Item

	'Collation
	https://learn.microsoft.com/en-us/sql/relational-databases/collations/collation-and-unicode-support?view=sql-server-ver16

	'Cách mã hóa UTF8 và UTF16
	https://cachthietkeweb.vn/utf-8-la-gi-tai-sao-chung-ta-can-hieu-ve-utf-8/
	https://symbl.cc/en/00C0/
	https://dvn.com.vn/so-hoa-ky-tu-la-viec-chuyen-ky-tu-thanh-1645576828/
	https://viblo.asia/p/little-endian-vs-big-endian-E375z0pWZGW#_little-endian-va-big-endian-duoc-dung-tren-nhung-may-tinh-nao-2
	https://www.rapidtables.com/convert/number/ascii-to-binary.html

	'3 cách chuyển decimal sang Hex trong SQL
	https://database.guide/3-ways-to-convert-decimal-to-hexadecimal-in-sql-server-t-sql/
	SELECT CONVERT(VARBINARY(8), 111) Result;
	SELECT CAST(111 AS VARBINARY(8)) Result;
	SELECT FORMAT(111, 'X') Result;

	'Hàm xem code point (điểm mã) của ký tự unicode
	select CAST(N'ơ' AS VARBINARY(16)) 
		-> trả về 0xA101
		-> Lấy byte sau ghép với byte đầu (do SQL dùng Little endian để ghi lên đĩa, Big endian thì ghi ngược lại) là 0x01A1
		-> Vào trang https://en.wikipedia.org/wiki/Latin_Extended-B
			dò trong bảng mã Latin mở rộng B sẽ thấy 0x01A1 chính là ký tự 'ơ'

	'Store xem unicode
	CREATE FUNCTION [dbo].[Find_Unicode]
	(
	    @in_string nvarchar(max)
	)
	RETURNS @unicode_char TABLE(id INT IDENTITY(1,1), Char_ NVARCHAR(4), position BIGINT)
	AS
	BEGIN
	    DECLARE @character nvarchar(1)
	    DECLARE @index int
	 
	    SET @index = 1
	    WHILE @index <= LEN(@in_string)
	    BEGIN
	        SET @character = SUBSTRING(@in_string, @index, 1)
	        IF((UNICODE(@character) NOT BETWEEN 32 AND 127) AND UNICODE(@character) NOT IN (10,11))
	        BEGIN
	      INSERT INTO @unicode_char(Char_, position)
	      VALUES(@character, @index)
	    END
	    SET @index = @index + 1
	    END
	    RETURN
	END


	'Difference between ANSI and ASCI
	https://www.tutorialspoint.com/difference-between-ansi-and-ascii
	https://www.rapidtables.com/convert/number/ascii-to-binary.html

	'Unicode
	https://vi.wikipedia.org/wiki/Unicode
	https://www.sqlshack.com/manage-unicode-characters-in-data-using-t-sql/

	'Unicode Plane
	https://en.wikipedia.org/wiki/Plane_(Unicode)#:~:text=Plane%200%20is%20the%20Basic,plane%2016%2C%20U%2B10FFFF.
	https://en.wikipedia.org/wiki/Basic_Latin_(Unicode_block)
	https://en.wikipedia.org/wiki/Latin-1_Supplement
	https://en.wikipedia.org/wiki/Latin_Extended-A
	https://en.wikipedia.org/wiki/Latin_Extended-B
	https://en.wikipedia.org/wiki/Plane_(Unicode)#:~:text=Plane%200%20is%20the%20Basic,plane%2016%2C%20U%2B10FFFF.
	https://en.wikipedia.org/wiki/Yi_Syllables
	
	https://learn.microsoft.com/en-us/sql/relational-databases/collations/collation-and-unicode-support?view=sql-server-ver16
	https://gotiengviet.com.vn/bang-ma-unicode/

	'Indentity in SQL
	https://simplesqltutorials.com/sql-server-identity-column/#:~:text=The%20IDENTITY%20property%20is%20set,are%20inserted%20into%20a%20table.
	SELECT IDENT_CURRENT ('BFODHG.dbo.[Value Entry]') AS Current_Identity;  

	ALTER TABLE [dhg gtsx2017] ADD PRIMARY KEY (RowID) --25 giây cho gần 1tr dòng

	CREATE NONCLUSTERED INDEX [IX_dhg gtsx2017] --9 giây cho gần 1tr dòng
	ON [dhg gtsx2017] (KHNam,Thang, Loai, Version,[Source Code], UserID,LoaiNhom)
	--include ()

	'INDEX(0) và INDEX(1): If a clustered index exists, INDEX(0) forces a clustered index scan, and INDEX(1) forces a clustered index scan or seek. If no clustered index exists, INDEX(0) forces a table scan, and INDEX(1) is interpreted as an error

	'Covering index
	CREATE NONCLUSTERED INDEX {index_name}  
	ON {table_name}(column_name...)   
	INCLUDE(column_name...)   -> Covering index
		The covering index is to store data on the index page, so that when searching for the corresponding data, as long as (miễn là) the index page is found, the data can be accessed, and there is no need to query the data page, so this index is data "covered".

	https://learn.microsoft.com/en-us/answers/questions/94659/can-we-create-cover-index-during-cluster-index-cre

	https://www.red-gate.com/simple-talk/databases/sql-server/learn/using-covering-indexes-to-improve-query-performance/#:%7E:text=%20Using%20Covering%20Indexes%20to%20Improve%20Query%20Performance,As%20illustrated%20in%20the%20preceding%20example%2C...%20More%20

	CREATE TABLE dbo.table1
	(c1 NVARCHAR(20) PRIMARY KEY CLUSTERED)

	declare @i int=0
	while @i<1000
	begin
		set @i=@i+1
		insert into table1(c1) select right('000'+convert(nvarchar,@i),3)
	end

	select * from table1 with (INDEX(0)) where c1='625'
	select * from table1 with (INDEX(1)) where c1='625'
	-> Xem excution plan

	'DeadLock trong SQL
	https://kb.pavietnam.vn/deadlock-trong-co-so-du-lieu-va-cach-phong-tranh.html
	
	'WITH (NOLOCK)
	https://www.sqlshack.com/understanding-impact-clr-strict-security-configuration-setting-sql-server-2017/
	https://www.sentryone.com/blog/aaronbertrand/bad-habits-nolock-everywhere
	https://sqlperformance.com/2015/04/t-sql-queries/the-read-uncommitted-isolation-level

	'How to check if a table is locked in sql server
	SELECT 
     SessionID = s.Session_id,
     resource_type,   
     DatabaseName = DB_NAME(resource_database_id),
     request_mode,
     request_type,
     login_time,
     host_name,
     program_name,
     client_interface_name,
     login_name,
     nt_domain,
     nt_user_name,
     s.status,
     last_request_start_time,
     last_request_end_time,
     s.logical_reads,
     s.reads,
     request_status,
     request_owner_type,
     objectid,
     dbid,
     a.number,
     a.encrypted ,
     a.blocking_session_id,
     a.text       
 FROM   
     sys.dm_tran_locks l
     JOIN sys.dm_exec_sessions s ON l.request_session_id = s.session_id
     LEFT JOIN   
     (
         SELECT  *
         FROM    sys.dm_exec_requests r
         CROSS APPLY sys.dm_exec_sql_text(sql_handle)
     ) a ON s.session_id = a.session_id
 WHERE  
     s.session_id > 50

	'Transaction Isolate Level
	https://learn.microsoft.com/en-us/sql/t-sql/statements/set-transaction-isolation-level-transact-sql?view=sql-server-ver16
	SET TRANSACTION ISOLATION LEVEL
	    { READ UNCOMMITTED
	    | READ COMMITTED
	    | REPEATABLE READ
	    | SNAPSHOT
	    | SERIALIZABLE
	    }
	select * from [Table Name] with (NOLOCK) --tương đương READ UNCOMMITTED
	select * from [Table Name] with (HOLDLOCK) --tương đương SERIALIZABLE
	

	'How do you find current database's transaction level on SQL Server?
	SELECT CASE transaction_isolation_level 
    		WHEN 0 THEN 'Unspecified' 
    		WHEN 1 THEN 'ReadUncommitted' 
    		WHEN 2 THEN 'ReadCommitted' 
    		WHEN 3 THEN 'Repeatable' 
    		WHEN 4 THEN 'Serializable' 
		   WHEN 5 THEN 'Snapshot' END AS TRANSACTION_ISOLATION_LEVEL 
	FROM sys.dm_exec_sessions 
	where session_id = @@SPID

	'OVERRIDE transaction_isolation_level BY TABLE HINT
	https://learn.microsoft.com/en-us/sql/t-sql/queries/hints-transact-sql-table?view=sql-server-ver16
	WITH  ( <table_hint> [ [ , ] ...n ] )

	<table_hint> ::=
	{ NOEXPAND [ , INDEX ( <index_value> [ , ...n ] ) | INDEX = ( <index_value> ) ]
	  | INDEX ( <index_value> [ , ...n ] ) | INDEX = ( <index_value> )
	  | FORCESEEK [ ( <index_value> ( <index_column_name> [ , ... ] ) ) ]
	  | FORCESCAN
	  | HOLDLOCK
	  | NOLOCK
	  | NOWAIT
	  | PAGLOCK
	  | READCOMMITTED
	  | READCOMMITTEDLOCK
	  | READPAST
	  | READUNCOMMITTED
	  | REPEATABLEREAD
	  | ROWLOCK
	  | SERIALIZABLE
	  | SNAPSHOT
	  | SPATIAL_WINDOW_MAX_CELLS = <integer_value>
	  | TABLOCK
	  | TABLOCKX
	  | UPDLOCK
	  | XLOCK
	}

	<table_hint_limited> ::=
	{
	    KEEPIDENTITY
	  | KEEPDEFAULTS
	  | HOLDLOCK
	  | IGNORE_CONSTRAINTS
	  | IGNORE_TRIGGERS
	  | NOLOCK
	  | NOWAIT
	  | PAGLOCK
	  | READCOMMITTED
	  | READCOMMITTEDLOCK
	  | READPAST
	  | REPEATABLEREAD
	  | ROWLOCK
	  | SERIALIZABLE
	  | SNAPSHOT
	  | TABLOCK
	  | TABLOCKX
	  | UPDLOCK
	  | XLOCK
	}

	https://viblo.asia/p/transaction-o-muc-do-co-lap-isolation-level-1ZnbRlWNv2Xo

	'Transactions with Memory-Optimized Tables (khác với các bảng nằm trên đĩa cứng)
	https://learn.microsoft.com/en-us/sql/relational-databases/in-memory-oltp/transactions-with-memory-optimized-tables?view=sql-server-ver16+

	'In-Memory OLTP overview and usage scenarios
	https://learn.microsoft.com/en-us/sql/relational-databases/in-memory-oltp/overview-and-usage-scenarios?view=sql-server-ver16

	'1 ví dụ tuyệt vời về Transaction Isolation Level
	https://sqlperformance.com/2015/04/t-sql-queries/the-read-uncommitted-isolation-level

	'SQL-Performance :	
		https://sqlperformance.com/category/archives/sql-performance
	    Conditional Order By:	https://sqlperformance.com/2012/08/t-sql-queries/conditional-order-by



	'Phát hiện RowID đạt tối đa
	https://www.mssqltips.com/sqlservertip/5554/sql-server-current-identity-value-report-for-all-tables/

	Tool:
SELECT A.TABLE_CATALOG AS CATALOG,
   A.TABLE_SCHEMA AS "SCHEMA",
   A.TABLE_NAME AS "TABLE",
   B.COLUMN_NAME AS "COLUMN",
   IDENT_SEED (A.TABLE_NAME) AS Seed,
   IDENT_INCR (A.TABLE_NAME) AS Increment,
   IDENT_CURRENT (A.TABLE_NAME) AS Curr_Value,
   B.DATA_TYPE as "Type",
   Type_Limit = CASE lower (B.DATA_TYPE)
      WHEN 'bigint'
         THEN '9,223,372,036,854,775,807'
      WHEN 'int'
         THEN '2,147,483,647'
      WHEN 'smallint'
         THEN '32,767'
      WHEN 'tinyint'
         THEN '255'
      WHEN 'decimal'  
         THEN REPLICATE ('9', B.NUMERIC_PRECISION)
      WHEN 'numeric'  
         THEN REPLICATE ('9', B.NUMERIC_PRECISION)
      END
FROM INFORMATION_SCHEMA.TABLES A, INFORMATION_SCHEMA.COLUMNS B
WHERE A.TABLE_CATALOG = B.TABLE_CATALOG AND 
      A.TABLE_SCHEMA = B.TABLE_SCHEMA AND 
     A.TABLE_NAME = B.TABLE_NAME AND 
     COLUMNPROPERTY (OBJECT_ID (B.TABLE_NAME), B.COLUMN_NAME, 'IsIdentity') = 1 AND 
     OBJECTPROPERTY (OBJECT_ID (A.TABLE_NAME), 'TableHasIdentity') = 1 AND 
     A.TABLE_TYPE = 'BASE TABLE'
ORDER BY A.TABLE_SCHEMA, A.TABLE_NAME

	'Index
	https://www.sqlshack.com/top-five-considerations-for-sql-server-index-design/#:~:text=SQL%20index%20is%20considered%20as,to%20retrieve%20a%20few%20records.
	
	'Tổ chức lưu trữ trong SQL
	https://quantricsdulieu.com/to-chuc-luu-tru-trong-sql-server-data-pages-data-rows/#:~:text=Page%20header%20l%C3%A0%20n%C6%A1i%20ch%E1%BB%A9a,%C4%91%E1%BA%A7u%20c%C3%A1c%20rows%20trong%20page.
	DBCC IND(0,'tblTest',1) --1925581898 1925581898
	SELECT * FROM sys.dm_db_page_info (5, 1, 642, DEFAULT);

	'DBCC IND
	https://sqlity.net/en/2204/dbcc-ind/

2/Thêm biến môi trường trong cmd:
	setx PATH "% PATH%; C: Python37 Scripts"
	setx PATH "% PATH%; C: Python 3.11.2 Scripts"
	
3/update lệnh pip:
	python.exe -m pip install --upgrade pip
	
4/Cài đặt gói ngoài (requests):
	pip install requests

5/Debug Python:
	Ctrl+F8 : bật/tắt breakpont  (giống F9 của VS Studio)
	F8: chạy từng bước (Step over)
	F7: chạy vô trong hàm (Step into)
	Shift+F10 : chạy bình thường
	Shift F9: chạy debug

6/Cài các gói ngoài thông dụng:
	pip install opencv-contrib-python
	pip install pandas

7/ Xem biến môi trường: gõ Environment Variables vào cmd, nhập user|pwd sau
	

8/

thanhhai@dhgpharma.com.vn
Dhg&2974&
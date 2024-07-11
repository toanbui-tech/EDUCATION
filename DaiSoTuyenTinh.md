- Khi tôi đọc mã, tôi gặp 1 trường hợp thế này:

```
TaskRepository
			BaseRepository
						JpaRepository, QuerydslPredicateExecutor
						

JpaRepository
			ListCrudRepository, ListPagingAndSortingRepository, QueryByExampleExecutor


ListCrudRepository
				CrudRepository
							Repository


ListPagingAndSortingRepository
						PagingAndSortingRepository
												Repository
```
Đoạn trên đang diễn tả các generic trong Java, và chúng extends, implements lồng nhau.
- Tôi cần phải ghi nhớ được cấu trúc tổng quan, để sớm nghĩ ra phương án giải quyết vấn đề
- Nhưng tôi cảm thấy rất khó ghi nhớ đoạn trên vào trí nhớ ngắn hạn của mình. Chúng quá nhiều

- Tôi nghĩ nếu tôi học thật kĩ về Đại số tuyến tính, Ma trận, hiểu được khuôn mẫu của nó, thì có lẽ tôi đã có thể nắm bắt được đống mã ở trên.

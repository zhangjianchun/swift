# swift
struct Ma {

	let rows: Int, columns: Int
	var grid: [Double]


	init(rows: Int, columns: Int) {
		self.rows = rows
		self.columns = columns
		grid = Array(count: rows * columns, repeatedValue: 0.0)
	}

	subscript(row: Int, column: Int) -> Double {
		get {

			return grid[(row * columns) + column]
		}
		set {

			grid[(row * columns) + column] = newValue
		}
	}
}

var matrix = Ma(rows: 2, columns: 2)
print(matrix.grid)//[0.0, 0.0, 0.0, 0.0]

matrix[0, 1] = 1.5
matrix[1, 0] = 3.2

print(matrix.grid)//[0.0, 1.5, 3.2, 0.0]
000000000000000000000000000000000000000000000
111111111111111111111111111111111111111111111
222222222222222222222222222222222222222222222

在商场新建个分支lenovo 加了这句！


在商场新建个分支lenovo 又又又又又又又又又又加了这句！


上面加了后 这里能传上网 家里下不了，也传不了！

找到问题了！他更新 我也更 他先上传 我要拉他更新下来到 另一个分支上 合并分支 ，现在上传！
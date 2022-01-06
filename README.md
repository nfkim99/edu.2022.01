<h1> 현택 😲 </h1>
<br>
<h4> 현택 </h4>

```java
	public String list3(Model model) {
		
		System.out.println("list()..");
		model.addAttribute("boardList", boardService.getList());
		
		return "board/tables";
	}
  ```

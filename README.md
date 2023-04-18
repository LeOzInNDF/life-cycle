# LifeCycle


![Angular-lifecycle](https://user-images.githubusercontent.com/112107085/232912863-c62b7ad3-d135-4004-be94-3ecf37c842ea.png)

	//checked -> contet -> view

	//quando o primeiro conteudo é iniciado
	ngAfterContentInit(): void {
		console.log('ngAfterContentInit');
	}

	//depois da inicialização da view
	ngAfterViewInit(): void {
		console.log('ngAfterViewInit');
	}

	//após alguma alteração, verifica o conteudo
	ngAfterContentChecked(): void {
		console.log('ngAfterContentChecked');
	}

	//após alguma alteração, verifica a view
	ngAfterViewChecked(): void {
		console.log('ngAfterViewChecked');
	}


	ngDoCheck(): void {
		console.log('ngDoCheck');
	}
	ngOnInit(): void {
		console.log('ngOnInit');
	}


	ngOnDestroy(): void {
		console.log("goodbye my friend")
	}
}

# Repository of custom hooks

## Elis Antonio Pérez

### React JS, Web

#### Hooks:
1. useCounter
2. useFetch
3. useForm

// Para crear snippets personalizados de Redux presiona control+Mayús+p y busca "Preferencias: Configurar fragmentos de usuario" ó "Preference: Configure user snippets", aparecen muchos archivos para cada tipo de documento, busca "javascript" y pega el contenido del siguiente objeto dentro de las llaves del objeto del documento "javascript" de VSCode.

{ // las curly brackets de apertura y cierre no, solo el contenido entre estos comentarios ↓↓↓

	"React-Redux useDispatch": {
		"prefix": "useDispatch",
		"body": [
			"const dispatch = useDispatch();",
		],
		"description": "Crea el useDispatch de React Redux"
	},
	"React-Redux useSelector": {
		"prefix": "useSelector",
		"body": [
			"const state = useSelector( state => state );",
		],
		"description": "Crea el useSelector de React Redux"
	},

} // las curly brackets de apertura y cierre no, solo el contenido entre estos comentarios ↑↑↑

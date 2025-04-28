ususario_correcto = input("crea tu nombre de ususario")
contraseña_correcta = input("crea tu contraseña")

usuario = input("escriba su nombre de usuario")
contraseña = input("escriba su contraseña")
if contraseña_correcta== contraseña and ususario_correcto== usuario:
    print("a iniciado sesion correctamente")
elif contraseña_correcta != contraseña:
    print("contraseña incorrecta, aqui tienes una pista: " + contraseña_correcta[0])
else:
    print("usuario incorrecto")

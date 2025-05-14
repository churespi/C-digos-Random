# C-digos-Random
Códigos random que eu fiz
print("Quem vai ser par, me diga seu nome")
par = io.read()
print ("quem vai ser impar, me diga seu nome")
impar = io.read()
print(par .. " me diga seu número")
nu1 = tonumber(io.read())
print(impar .. " me diga seu número")
nu2 = tonumber(io.read())

soma = nu1 + nu2
print (par .. " escolheu: " ..  nu1 .. ", "  ..  impar  .. " escolheu: " .. nu2 )
total = soma % 2 

function verifPoI(total)
  if total == 0 then
     print (par ..  " que é par")
     
  elseif total == 1 then 
    print (impar ..  " que é impar")
    
  else 
    print("está inválido")
    
  end
  
end 

print ("quem venceu foi ") verifPoI(total)

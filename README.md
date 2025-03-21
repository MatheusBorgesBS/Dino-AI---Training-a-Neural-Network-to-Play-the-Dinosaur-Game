import pygame

pygame.init()

size = width, height = 640, 480

game_display = pygame.display.set_mode(size)
running = True

altura_chao = height-100
preto = 0,0,0
branco = 255, 255, 255
xPos = 0
yPos = 0
while running:
    for event in pygame.event.get():    
        if event.type == pygame.QUIT:
            pygame.quit()
            running = False
    pygame.draw.rect(game_display, branco, [30,30,40,50])
    
    pygame.display.update()

           

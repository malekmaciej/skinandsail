# skinandsail
Infrastructure for building skinandsail.org web galleries
# #   R e q u i r e m e n t s  
  
 N o   r e q u i r e m e n t s .  
  
 # #   P r o v i d e r s  
  
 |   N a m e   |   V e r s i o n   |  
 | - - - - - - | - - - - - - - - - |  
 |   < a   n a m e = " p r o v i d e r _ a w s " > < / a >   [ a w s ] ( # p r o v i d e r \ _ a w s )   |   5 . 4 1 . 0   |  
  
 # #   M o d u l e s  
  
 |   N a m e   |   S o u r c e   |   V e r s i o n   |  
 | - - - - - - | - - - - - - - - | - - - - - - - - - |  
 |   < a   n a m e = " m o d u l e _ a c m " > < / a >   [ a c m ] ( # m o d u l e \ _ a c m )   |   t e r r a f o r m - a w s - m o d u l e s / a c m / a w s   |   5 . 0 . 0   |  
  
 # #   R e s o u r c e s  
  
 |   N a m e   |   T y p e   |  
 | - - - - - - | - - - - - - |  
 |   [ a w s _ c l o u d f r o n t _ d i s t r i b u t i o n . t h i s ] ( h t t p s : / / r e g i s t r y . t e r r a f o r m . i o / p r o v i d e r s / h a s h i c o r p / a w s / l a t e s t / d o c s / r e s o u r c e s / c l o u d f r o n t _ d i s t r i b u t i o n )   |   r e s o u r c e   |  
 |   [ a w s _ r o u t e 5 3 _ r e c o r d . d n s _ n a m e _ c i v e t t a 2 0 2 4 ] ( h t t p s : / / r e g i s t r y . t e r r a f o r m . i o / p r o v i d e r s / h a s h i c o r p / a w s / l a t e s t / d o c s / r e s o u r c e s / r o u t e 5 3 _ r e c o r d )   |   r e s o u r c e   |  
 |   [ a w s _ s 3 _ b u c k e t . c i v e t t a 2 0 2 4 ] ( h t t p s : / / r e g i s t r y . t e r r a f o r m . i o / p r o v i d e r s / h a s h i c o r p / a w s / l a t e s t / d o c s / r e s o u r c e s / s 3 _ b u c k e t )   |   r e s o u r c e   |  
 |   [ a w s _ s 3 _ b u c k e t _ p o l i c y . t h i s ] ( h t t p s : / / r e g i s t r y . t e r r a f o r m . i o / p r o v i d e r s / h a s h i c o r p / a w s / l a t e s t / d o c s / r e s o u r c e s / s 3 _ b u c k e t _ p o l i c y )   |   r e s o u r c e   |  
 |   [ a w s _ s 3 _ b u c k e t _ p u b l i c _ a c c e s s _ b l o c k . e x a m p l e ] ( h t t p s : / / r e g i s t r y . t e r r a f o r m . i o / p r o v i d e r s / h a s h i c o r p / a w s / l a t e s t / d o c s / r e s o u r c e s / s 3 _ b u c k e t _ p u b l i c _ a c c e s s _ b l o c k )   |   r e s o u r c e   |  
 |   [ a w s _ s 3 _ b u c k e t _ w e b s i t e _ c o n f i g u r a t i o n . w e b s i t e ] ( h t t p s : / / r e g i s t r y . t e r r a f o r m . i o / p r o v i d e r s / h a s h i c o r p / a w s / l a t e s t / d o c s / r e s o u r c e s / s 3 _ b u c k e t _ w e b s i t e _ c o n f i g u r a t i o n )   |   r e s o u r c e   |  
  
 # #   I n p u t s  
  
 |   N a m e   |   D e s c r i p t i o n   |   T y p e   |   D e f a u l t   |   R e q u i r e d   |  
 | - - - - - - | - - - - - - - - - - - - - | - - - - - - | - - - - - - - - - | : - - - - - - - - : |  
 |   < a   n a m e = " i n p u t _ c i v e t t a 2 0 2 4 _ d o m a i n " > < / a >   [ c i v e t t a 2 0 2 4 \ _ d o m a i n ] ( # i n p u t \ _ c i v e t t a 2 0 2 4 \ _ d o m a i n )   |   D o m a i n   n a m e   f o r   C i v e t t a   2 0 2 4   g a l l e r y   |   ` s t r i n g `   |   ` " c i v e t t a 2 0 2 4 . s k i a n d s a i l . o r g " `   |   n o   |  
 |   < a   n a m e = " i n p u t _ r e g i o n " > < / a >   [ r e g i o n ] ( # i n p u t \ _ r e g i o n )   |   R e g i o n   w h e r e   S 3   b u c k e t   l o c a t e d   |   ` s t r i n g `   |   ` " e u - c e n t r a l - 1 " `   |   n o   |  
 |   < a   n a m e = " i n p u t _ t a g s " > < / a >   [ t a g s ] ( # i n p u t \ _ t a g s )   |   T a g s   f o r   a l l   r e s o u r c e s   |   ` m a p ( s t r i n g ) `   |   < p r e > { < b r >     " g i t r e p o " :   " h t t p s : / / g i t h u b . c o m / m a l e k m a c i e j / s k i n a n d s a i l " , < b r >     " o w n e r " :   " m a l e k m a c i e j " < b r > } < / p r e >   |   n o   |  
 |   < a   n a m e = " i n p u t _ z o n e _ i d " > < / a >   [ z o n e \ _ i d ] ( # i n p u t \ _ z o n e \ _ i d )   |   T h e   I D   o f   t h e   h o s t e d   z o n e   t o   c o n t a i n   t h i s   r e c o r d .   R e q u i r e d   w h e n   v a l i d a t i n g   v i a   R o u t e 5 3   |   ` s t r i n g `   |   ` " Z 0 1 3 8 1 1 5 2 7 X F 2 2 U Y 5 W H I E " `   |   n o   |  
  
 # #   O u t p u t s  
  
 N o   o u t p u t s .  
 
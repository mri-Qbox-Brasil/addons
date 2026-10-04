# mri_props

Props que os resources da MRI usam. Ficam aqui, fora dos scripts, para que reiniciar um script não remonte arquivo streamado no cliente de quem está conectado (isso derruba o jogo).

| Modelo | Usado por |
|---|---|
| `rojo_jblboombox` | `mri_Qsoundfyapp` (caixa de som JBL, na mão e no chão) |

Cada prop que tem `.ytyp` precisa dos arquivos que o `.ytyp` cita: a JBL usa `.ydr`, `.ytd` e o `.ycd` (animação). Sem o `.ycd` o modelo não carrega.
